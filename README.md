# DockerComposeMaxiMus
 Hi and welcome.

In this docker file we find a lot of services together working under traefik reverse proxy.
No one of volumes are correctly configurated, you need to put YOUR volumes.

## LIST OF SERVICES:

* Traefik
* Portainer
* Plex
* Rclone (YOU NEED TO DO THE CONFIGURATION BY YOURSELF. THIS ALLOWS YOU TO USE ANY TYPE OF STORAGE AS IT IS CONNECTED DIRECTLY TO THE SYSTEM. Ex:Google Drive)
* Qbittorrent
* Tautulli
* Sonarr
* Rocket-Chat
    * Mongo
    * Mongo-init-replica
* Radarr
* Prometheus
     * Node-exporter
* Medusa
* Lidarr
* Jackett
* Firefly
    * FireflyDB
* Bazarr
