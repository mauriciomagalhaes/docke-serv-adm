# Docker-Servadm
Docker Serviços Admins 

# Serviços:
- Letscript
- Grafana
- Zabbix 5.0 latest LTS
- Zabbix Agent 5.0 latest LTS
- Nextcloud
- Glpi
- Graylog
    - Mongodb
    - Elastcsearch
    - Graylog

# Criar diretorios e direitos

# ELASTICSEARCH
    # sudo mkdir -p /var/docker/graylog/elasticsearch/data
    # sudo chmod 777 /var/docker/graylog/elasticsearch/data
# GRAFANA
    # sudo chown -R 472:472 /var/docker/grafana/data
    # sudo chmod -R 775 /var/docker/grafana