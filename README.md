# Docker-Servadm
Docker Serviços Admins 

# Serviços:
- Nginx proxy https with letsencrypt
    - Glpi
    - Grafana
    - Graylog
        - Graylog Web/API
        - Elasticsearch
        - Mongodb
    - Nextcloud
    - Zabbix 5.0 latest LTS
        - zabbix Server 5.0 latest LTS
        - Zabbix Agent 5.0 latest LTS
        - Zabbix Web 5.0 latest LTS

# Criar diretorios e direitos:

# ELASTICSEARCH
    # sudo mkdir -p /var/docker/graylog/elasticsearch/data
    # sudo chmod 777 /var/docker/graylog/elasticsearch/data
# GRAFANA
    # sudo chown -R 472:472 /var/docker/grafana/data
    # sudo chmod -R 775 /var/docker/grafana