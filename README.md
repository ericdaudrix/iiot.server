<b>Deploiement serveur pour l'internet des objets industriels</b>

proxy.sh script de parametrage du proxy (optionnel à exécuter avant le script d'installation si votre serveur est derrière un proxy)
config.sh script d'installation des services

<b>Prérequis:</b>
- raspberry pi os lite (64bits)


<b>services installés:</b>
- node-red port 1880
- influxdb port 8086
- grafana port 3000
- broker mqtt mosquito port 1883
- portainer (9000 ou 9443 en https)

<b>identifiants et mot de passe par défaut:</b>
- portainer (admin/pass4portainer)
- grafana (admin/admin)

<b>base de donnée influxdb:</b>
demo (anonyme)
persistance: 24h

