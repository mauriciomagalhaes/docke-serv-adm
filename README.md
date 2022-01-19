# Docker-Servadm
Docker Serviços Admins 

# Serviços:
- Nginx proxy manager                       # Servidor de administração proxy http
    - Glpi latest                           # Sistema de Suporte Tickets
    - MariaDB latest                        # Banco de Dados MariaDB
    - Nextcloud latest                      # Sistema de Cloud, armazenamento e comp. de arquivos
        - Collabora latest
    - Zabbix 5.0 LTS                        # Monitoramento de serviços
        - zabbix Server 5.0 latest LTS      # Zabbix Server
        - Zabbix Agent 5.0 latest LTS       # Zabbix Agent
        - Zabbix Web 5.0 latest LTS         # Zabbix Web
    - Grafana                               # Dashboards
        - Prometeus latest                  
        - Alertmanager latest
        - Node Exporter latest
        - Loki
    - Heplify-server                        # Monitoramento SIP
        - Homer-webapp                      # Monitoramento SIP Dashboard
    - PostgreSQL 11-alpine                  # Banco de dados Postgresql
    - Remotely                              # Sistema de acesso remoto via ID (Anydesk)
    - Meshcenter                            # Sistema de acesso remoto via Agente
    - Portainer                             # Administrador de Dockers
    - Homer-dashboard                       # Dashboard de Serviços


# Criar diretorios e direitos:
    
# GRAFANA:
    # sudo chown -R 472:472 /var/docker/grafana/data
    # sudo chmod -R 775 /var/docker/grafana