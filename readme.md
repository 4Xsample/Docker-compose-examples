<a href="https://www.paypal.com/donate/?hosted_button_id=EFVMSRHVBNJP4">
<img src="https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white" alt="PayPal"></a></br>

<a href="https://discord.gg/ahVq54p">
<img src="https://img.shields.io/discord/667340023829626920?logo=discord" alt="chat on Discord"></a></br>

<a href="https://twitter.com/4xsample/follow?screen_name=shields_io">
<img src="https://img.shields.io/twitter/follow/4xsample?style=social&logo=twitter" alt="follow on Twitter"></a>

# Contenidors a punt per desplegar.

Aquests docker-compose.yml estan tal com estan, no necessiten altres arxius .config ni altres detalls.

M'han funcionat amb un exit mitjà en una [raspberry pi 4](https://www.raspberrypi.com/products/raspberry-pi-4-model-b/) amb [raspberry pi os](https://www.raspberrypi.com/software/) actualitzat a la ultima versió, funcionant en la ultima versió de [docker](https://www.docker.com) i administrat des de la versió mes recent de [portainer](https://www.portainer.io) disponible.


### Media Servers

[Plex](https://app.plex.tv): Plex es el servidor domestic de contingut que ens permet tenir disponibles tots els continguts que els nostres serveis de stram no ens ofereixen.

[ruTorrent](https://hub.docker.com/r/linuxserver/rutorrent): ruTorrent es una excelent interficie d'usuari via web per rTorrent (desgraciadament no te per posar codi d'acces)

[Organizr](https://organizr.us) o [Organizr Reddit](https://www.reddit.com/r/organizr/): Organizr integra tots els serveis de la teva xarxa en una sola web. Ja no haurem de recordar una dotzena de ips i ports diferents per accedir a tot. Avui en dia es el millor frontend per servidors domestics (o no tant domestics).

[Portainer](https://portainer.io): Portainer es una interficie Open-Source lleugera per administrar hosts de Docker o eixams de clusters.

[NetData](https://my-netdata.io): El visualitzador definitiu en temps deal de tot el que passa als teus sistemes i aplicacions.