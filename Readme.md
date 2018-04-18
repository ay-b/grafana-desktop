# Complete Graphana monitoring for docker-compose  
*No persistent storage by default!*  
*That means that every `docker-compose down` will destroy all collected data!*  

**This is an on-desk development setup, so there is no security features of any kind and all ports are exposed!**  
Feel free to play with compose-file and tune it to fit your needs.


## InfluxDB
Docker image: https://hub.docker.com/_/influxdb/  

## Chronograf
Admin UI for Influxdb: http://localhost:8087/  

## Telegraf
Docker image: https://hub.docker.com/r/appcelerator/telegraf/  
See parameters at the image description  

## Grafana
Docker image: https://hub.docker.com/r/appcelerator/grafana/  
See parameters at the image description  
Web-UI: http://localhost:8000/  

