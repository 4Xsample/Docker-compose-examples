
|               |               |               |               |               |               |
|:-------------:|:-------------:|:-------------:|-------------:|-------------:|-------------:|
| ![Hack the planet](https://img.shields.io/badge/Hack-The%20Planet-orange) | [![Discord](https://img.shields.io/discord/667340023829626920?logo=discord)](https://discord.gg/ahVq54p) | [![Twitter](https://img.shields.io/twitter/follow/4xsample?style=social&logo=twitter)](https://twitter.com/4xsample/follow?screen_name=shields_io) | [![4Xsample@mastodon.social](https://img.shields.io/badge/Mastodon-@4Xsample-blueviolet?style=for-the-badge&logo=mastodon)](https://mastodon.social/@4Xsample) | [![4Xsample](https://img.shields.io/badge/Twitch-4Xsample-6441A4?style=for-the-badge&logo=twitch)](https://twitch.tv/4Xsample) | [![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.com/donate/?hosted_button_id=EFVMSRHVBNJP4) |


# Homebridge
### [Apple Homekit](https://www.apple.com/ios/home/) per tothom.

[Homebridge](https://homebridge.io) by [Nfarina's](https://github.com/nfarina) es la solució per integrar dispositius i serveis no compatibles amb [Apple Homekit](https://www.apple.com/ios/home/).

Usant el .yml
```yml
version: '2'
services:
  homebridge:
    image: oznu/homebridge:ubuntu
    restart: always
    network_mode: host
    environment:
      - PGID=1000
      - PUID=1000
      - HOMEBRIDGE_CONFIG_UI=1
      - HOMEBRIDGE_CONFIG_UI_PORT=8581
      - TZ=Europe/Andorra
    volumes:
      - ./volumes/homebridge:/homebridge
```

## Homebridge UI

Aquesta imatge porta de serie la interficie d'usuari [Homebridge UI](https://github.com/oznu/homebridge-config-ui-x) i es la forma mes senzilla d'administrar tots els aspectes de [Homebridge](https://homebridge.io).

* `-e HOMEBRIDGE_CONFIG_UI=1` - Set to `0` Per desactivar el [Homebridge UI](https://github.com/oznu/homebridge-config-ui-x).
* `-e HOMEBRIDGE_CONFIG_UI_PORT=8581` - Per cambiar el port del [Homebridge UI](https://github.com/oznu/homebridge-config-ui-x). Per defecte s'usa el 8581.

Per entrar a la interficie [Homebridge UI](https://github.com/oznu/homebridge-config-ui-x) es pot acedir a `http://x.x.x.x:8581` on x.x.x.x es la ip del dispositiu on corre [Homebridge](https://homebridge.io). Per exemple `http://192.168.1.2:8581`. des d'aquí es pot instalar, configurar i treure plugins al mateix temps que es pot editar el `config.json` de [Homebridge](https://homebridge.io) i reiniciar-lo si es necessari.

El nom d'usuari per defecte es **`admin`** i el codi d'acces es **`admin`**.

<p align="left">
  <img width="600px" src="https://user-images.githubusercontent.com/3979615/71886653-b16d3f80-3190-11ea-9ff8-49dc4ae4fff0.png">
</p>

##### Configuració opcional:

* `-e PGID` - Important definir la ID del grup d'usuari
* `-e PUID` - Important definir la ID de l'usuari
* `-e TZ` - Per [Informació dels fusos horaris](https://ca.wikipedia.org/wiki/Base_de_dades_tz) e.g. `-e TZ=Europe/Andorra`

## Disclaimer: 
*Aquest codi s'ofereix tal com és i no es garanteix que funcioni correctament en totes les condicions. No em faig responsable dels danys que puguin resultar de l'ús d'aquesta informació. Utilitzeu-lo sota la vostra pròpia responsabilitat. Si teniu dubtes pregunteu i respondré al que pugui. Si voleu obrir proposar cambis podeu obrir fork i i voleu seguir-me, al panel del principi d'aquest readme podeu trobar links a les meves xarxes socials, Twitch i PayPal per si també voleu donar suport al meu treball.*