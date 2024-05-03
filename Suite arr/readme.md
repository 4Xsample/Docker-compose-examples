|               |               |               |               |               |               |
|:-------------:|:-------------:|:-------------:|-------------:|-------------:|-------------:|
| ![Hack the planet](https://img.shields.io/badge/Hack-The%20Planet-orange) | [![Discord](https://img.shields.io/discord/667340023829626920?logo=discord)](https://discord.gg/ahVq54p) | [![Twitter](https://img.shields.io/twitter/follow/4xsample?style=social&logo=twitter)](https://twitter.com/4xsample/follow?screen_name=shields_io) | [![4Xsample@mastodon.social](https://img.shields.io/badge/Mastodon-@4Xsample-blueviolet?style=for-the-badge&logo=mastodon)](https://mastodon.social/@4Xsample) | [![4Xsample](https://img.shields.io/badge/Twitch-4Xsample-6441A4?style=for-the-badge&logo=twitch)](https://twitch.tv/4Xsample) | [![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.com/donate/?hosted_button_id=EFVMSRHVBNJP4) |

# Suite ARR - Automatització de Gestió de Contingut Multimedia

La Suite ARR és una col·lecció de software de codi obert dissenyada per a l'automatització de la gestió de contingut multimèdia, incloent-hi la gestió de pel·lícules, sèries, música i altres mitjans. Aquest conjunt de programari està compost per diversos components, incloent-hi Radarr, Sonarr, Lidarr, Prowlarr, Qbittorrent, i Tautulli.

## Components de la Suite ARR

- **Radarr**: Un gestor de pel·lícules que facilita la descàrrega automàtica, la gestió i la catalogació de pel·lícules. Pots accedir a Radarr a través de [http://localhost:7878](http://localhost:7878).
- **Sonarr**: Similar a Radarr, però enfocat en la gestió de sèries de televisió. Pots accedir a Sonarr a través de [http://localhost:8989](http://localhost:8989).
- **Lidarr**: Orientat a la gestió de música, permetent la cerca i descàrrega de àlbums musicals. Pots accedir a Lidarr a través de [http://localhost:8686](http://localhost:8686).
- **Prowlarr**: Un servei de cerca unificada que permet als usuaris accedir a diverses fonts de contingut, com ara trackers privats, sense necessitat de comptes. Pots accedir a Prowlarr a través de [http://localhost:9696](http://localhost:9696).
- **Qbittorrent**: Un client BitTorrent lleuger, ràpid i eficient amb una interfície web fàcil d'utilitzar per a la descàrrega de contingut multimèdia. Pots accedir a Qbittorrent a través de [http://localhost:8080](http://localhost:8080).
- **Tautulli**: Un servidor de monitoratge i anàlisi de Plex Media Server que ofereix estadístiques detallades sobre l'ús del servidor. Pots accedir a Tautulli a través de [http://localhost:8181](http://localhost:8181).

## Opcions de Desplegament

La Suite ARR ofereix flexibilitat en la manera com es poden desplegar els seus components. Podeu optar per desplegar tots els contenidors alhora com a stack, utilitzant eines com Docker Compose o Kubernetes. Això facilita la gestió i la escalabilitat del conjunt de programari.

També és possible desplegar els contenidors de forma independent, segons les necessitats del vostre entorn. Malgrat que aquests components estan dissenyats per treballar junts i alguns poden dependre d'altres (per exemple, Prowlarr pot servir com a directori de cerca per als altres gestors), també es poden utilitzar de manera autònoma.

Els gestors necessiten accedir a un client de descarregues per funcionar correctament, però aquests clients es poden instal·lar per separat i poden funcionar en combinació amb altres programes en lloc dels especificats aquí. Tot i així, la combinació de Radarr, Sonarr, Lidarr, Prowlarr, Qbittorrent i Tautulli és una configuració que ha demostrat ser eficaç i completa per a la gestió de contingut multimèdia.

## Integració i Avantatges

La integració d'aquests diferents elements de la Suite ARR ofereix diversos avantatges:

- **Automatització**: Amb la configuració adequada, la Suite ARR pot automatitzar la cerca, descàrrega i organització del contingut multimèdia, estalviant temps i esforços a l'usuari.
- **Gestió centralitzada**: Amb una sola interfície per a tota la gestió de contingut multimèdia, els usuaris poden tenir un control centralitzat sobre les seves biblioteques de pel·lícules, sèries i música.
- **Optimització de l'espai de disc**: Les opcions de configuració avançada permeten als usuaris controlar l'espai de disc utilitzat per al contingut multimèdia, optimitzant la seva emmagatzematge i gestió.
- **Monitoratge i informes**: Tautulli ofereix estadístiques detallades sobre l'ús del servidor Plex, permetent als usuaris monitorar i analitzar el comportament dels seus usuaris i la qualitat del servei.

## Disclaimer: 
*Aquest codi s'ofereix tal com és i no es garanteix que funcioni correctament en totes les condicions. No em faig responsable dels danys que puguin resultar de l'ús d'aquesta informació. Utilitzeu-lo sota la vostra pròpia responsabilitat. Si teniu dubtes pregunteu i respondré al que pugui. Si voleu obrir proposar canvis podeu obrir fork i i voleu seguir-me, al panel del principi d'aquest readme podeu trobar links a les meves xarxes socials, Twitch i PayPal per si també voleu donar suport al meu treball.*