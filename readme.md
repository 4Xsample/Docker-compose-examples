
|               |               |               |               |               |               |
|:-------------:|:-------------:|:-------------:|-------------:|-------------:|-------------:|
| ![Hack the planet](https://img.shields.io/badge/Hack-The%20Planet-orange) | [![Discord](https://img.shields.io/discord/667340023829626920?logo=discord)](https://discord.gg/ahVq54p) | [![Twitter](https://img.shields.io/twitter/follow/4xsample?style=social&logo=twitter)](https://twitter.com/4xsample/follow?screen_name=shields_io) | [![4Xsample@mastodon.social](https://img.shields.io/badge/Mastodon-@4Xsample-blueviolet?style=for-the-badge&logo=mastodon)](https://mastodon.social/@4Xsample) | [![4Xsample](https://img.shields.io/badge/Twitch-4Xsample-6441A4?style=for-the-badge&logo=twitch)](https://twitch.tv/4Xsample) | [![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.com/donate/?hosted_button_id=EFVMSRHVBNJP4) |



# Repositori de Docker Compose pel Home Lab

Aquest repositori conté els fitxers Docker Compose que he utilitzat per configurar el meu home lab. Cada carpeta del repositori correspon a un servei o aplicació concreta, i inclou el fitxer `docker-compose.yml` amb la configuració dels containers.

## Contenidors a punt per desplegar.

Aquests docker-compose.yml estan tal com estan, no necessiten altres arxius .config ni altres detalls.

Per utilitzar un dels compose files, es pot fer servir el comandament `docker-compose up -d` des de la línia de comandes o bé es pot importar el fitxer `docker-compose.yml` a Portainer com a stack. En el meu cas, he comprovat que aquest últim mètode funciona amb èxit en una [raspberry pi 4](https://www.raspberrypi.com/products/raspberry-pi-4-model-b/) amb [raspberry pi os](https://www.raspberrypi.com/software/) actualitzat a la última versió, funcionant en la última versió de [docker](https://www.docker.com) i administrat des de la versió més recent de [portainer](https://www.portainer.io) disponible.

Assegureu-vos de tenir instal·lat [docker](https://www.docker.com) al vostre sistema abans de desplegar els contenidors.

Estic obert a suggeriments o millores dels fitxers Docker Compose. Si voleu fer alguna contribució, no dubteu en fer un pull request al repositori.

Estic disposat a ajudar en qualsevol dubte o problema que puguis tenir en relació amb els fitxers Docker Compose del repositori. No dubteu en obrir una issue si ho necessiteu.

## Home Lab

[Portainer](https://portainer.io): Portainer es una interficie Open-Source lleugera per administrar hosts de Docker o eixams de clusters.

[Organizr](https://organizr.us) o [Organizr Reddit](https://www.reddit.com/r/organizr/): Organizr integra tots els serveis de la teva xarxa en una sola web. Ja no haurem de recordar una dotzena de ips i ports diferents per accedir a tot. Avui en dia es el millor frontend per servidors domestics (o no tant domestics).

[Plex](https://app.plex.tv): Plex es el servidor domestic de contingut que ens permet tenir disponibles tots els continguts que els nostres serveis de stram no ens ofereixen.

[Pi-Hole](https://pi-hole.net) es un filtre de publicitat per DNS que protegeix tots els dispositius conectats a la meva xarxa de la publicitat a la xarxa.

[ruTorrent](https://hub.docker.com/r/linuxserver/rutorrent): ruTorrent es una excelent interficie d'usuari via web per rTorrent (desgraciadament no te per posar codi d'acces)

[Transmission](https://transmissionbt.com): Un bon client de torrent amb interficie via web.

[NetData](https://my-netdata.io): El visualitzador definitiu en temps deal de tot el que passa als teus sistemes i aplicacions.

[NginX Proxy Manager](https://nginxproxymanager.com): Es un servidor proxy molt lleuger basat en el servidor web [NginX](https://www.nginx.com).

[uBooquity](https://vaemendis.net/ubooquity/): Es el servidor de eBooks, en diversos formats, per poder accedir des d'arreu als nostres llibres i pdf.

[Shellinabox](https://github.com/shellinabox/shellinabox) Es una solució interessant per poder accedir a la consola via web sense necessitar un client de ssh.

[ruTorrent](https://github.com/Novik/ruTorrent) es una interficie web per gestionar el [rTorrent](https://github.com/rakshasa/rtorrent) molt versatil i completa (falta trastejar-lo una mica encara).

[php:8.0-apache](https://hub.docker.com/r/oberd/php-8.0-apache) es una imatge preparada per desplegar rapid i facil un servidor apache senzill amb php, per poder fer alguna prova.

[itzg/minecraft-server](https://hub.docker.com/r/itzg/minecraft-server) es la forma mes ràpida de desplegar un servidor de [minecraft](https://www.minecraft.net/).

[linuxserver/code-server](https://hub.docker.com/r/linuxserver/code-server) es l'editor [Visual Studio](https://visualstudio.microsoft.com/) via web per excelencia!

[Homebridge](https://homebridge.io) es la solució per integrar dispositius i serveis no compatibles amb [Apple Homekit](https://www.apple.com/ios/home/).

## Disclaimer: 
*Aquest codi s'ofereix tal com és i no es garanteix que funcioni correctament en totes les condicions. No em faig responsable dels danys que puguin resultar de l'ús d'aquesta informació. Utilitzeu-lo sota la vostra pròpia responsabilitat. Si teniu dubtes pregunteu i respondré al que pugui. Si voleu obrir proposar cambis podeu obrir fork i i voleu seguir-me, al panel del principi d'aquest readme podeu trobar links a les meves xarxes socials, Twitch i PayPal per si també voleu donar suport al meu treball.*