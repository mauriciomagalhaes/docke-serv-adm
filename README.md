# Docker-Servadm
Docker Serviços Admins 

# Serviços:
- Nginx proxy manager
    - Glpi latest
    - Grafana latest
    - MariaDB latest
    - Nextcloud latest
        - Collabora latest
    - Zabbix 5.0 LTS
        - zabbix Server 5.0 latest LTS
        - Zabbix Agent 5.0 latest LTS
        - Zabbix Web 5.0 latest LTS
    - Grafana
        - Prometeus latest
        - Alertmanager latest
        - Node Exporter latest
        - Loki
    - Heplify-server
        - Homer-webapp
    - PostgreSQL 11-alpine
    - Remotely
    - Meshcenter
    - Portainer
    - Homer-dashboard


# Criar diretorios e direitos:

# ELASTICSEARCH:
    # sudo mkdir -p /var/docker/graylog/elasticsearch/data
    # sudo chmod 777 /var/docker/graylog/elasticsearch/data
    
# GRAFANA:
    # sudo chown -R 472:472 /var/docker/grafana/data
    # sudo chmod -R 775 /var/docker/grafana