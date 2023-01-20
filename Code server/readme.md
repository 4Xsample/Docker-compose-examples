
|               |               |               |               |               |               |
|:-------------:|:-------------:|:-------------:|-------------:|-------------:|-------------:|
| ![Hack the planet](https://img.shields.io/badge/Hack-The%20Planet-orange) | [![Discord](https://img.shields.io/discord/667340023829626920?logo=discord)](https://discord.gg/ahVq54p) | [![Twitter](https://img.shields.io/twitter/follow/4xsample?style=social&logo=twitter)](https://twitter.com/4xsample/follow?screen_name=shields_io) | [![4Xsample@mastodon.social](https://img.shields.io/badge/Mastodon-@4Xsample-blueviolet?style=for-the-badge&logo=mastodon)](https://mastodon.social/@4Xsample) | [![4Xsample](https://img.shields.io/badge/Twitch-4Xsample-6441A4?style=for-the-badge&logo=twitch)](https://twitch.tv/4Xsample) | [![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.com/donate/?hosted_button_id=EFVMSRHVBNJP4) |



# Code Server

Aquest repositori conté el fitxer `docker-compose.yml` per a executar [Code Server](https://github.com/cdr/code-server) a través de Docker.

## Què és Code Server?

Code Server és una implementació del Visual Studio Code com a aplicació web. Això significa que podeu executar Visual Studio Code a qualsevol navegador, ja sigui a la vostra màquina local o a qualsevol altra màquina a través d'internet. Això és molt útil si voleu utilitzar Visual Studio Code en un entorn remot, com ara un servidor, sense haver d'instal·lar-lo directament en aquesta màquina.

## Com utilitzar aquest repositori

1. Assegureu-vos que teniu instal·lat Docker en la vostra màquina. Podeu descarregar Docker [aquí](https://www.docker.com/get-started).
2. Cloneu aquest repositori o descarregueu-lo com a zip.
3. A la carpeta del repositori, executeu el comandament `docker-compose up -d` per iniciar el contenidor de Code Server.
4. Obrir el navegador i anar a l'adreça `http://localhost:8443`. Això hauria d'obrir l'aplicació de Code Server.

## Disclaimer: 
*Aquest codi s'ofereix tal com és i no es garanteix que funcioni correctament en totes les condicions. No em faig responsable dels danys que puguin resultar de l'ús d'aquesta informació. Utilitzeu-lo sota la vostra pròpia responsabilitat. Si teniu dubtes pregunteu i respondré al que pugui. Si voleu obrir proposar cambis podeu obrir fork i i voleu seguir-me, al panel del principi d'aquest readme podeu trobar links a les meves xarxes socials, Twitch i PayPal per si també voleu donar suport al meu treball.*