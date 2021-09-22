## Monitoringtoolkit using jmeter,influxDB & Grafana
* It automates jmeter executions and shows live results in grafana dashboard using docker compose easily
* Create a folder under which docker-compose file resides and add grafana,influxdb and jmeter folder to store the dockerfile and concerned config and data files
* Tweak the jmeter script and data files according to your need and i'm using sample jpetstore demo jmeter script file for execution.
* Update the jmeter dockerfile accordingly based on your requirement 
* Update the docker compose file according to your need.
* Use docker container name to establish connection between containers.

![Docker-Compose output](https://github.com/manojkumar542/Monitoringtoolkit/blob/Update/Docker-compose.JPG)
