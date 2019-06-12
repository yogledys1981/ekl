#Implementación de ELK Stack como plataforma de monitoreo que permita mejorar la capacidad de diagnostico ante fallas o problemas de disponibilidad del software ATIX ERP


### Comandos

`make upd` ejecuta el compose en segundo plano

`make down` detiene ELK

`make delete` elimina los containers

### Información

Iniciar kibana en esta ruta [http://localhost:5601](http://localhost:5601).

Puertos por defecto:
* 5044: Logstash beat input.
* 9200: Elasticsearch HTTP.
* 5601: Kibana.
