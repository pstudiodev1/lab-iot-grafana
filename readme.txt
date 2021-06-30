MQTT Client
- mqtt://127.0.0.1:10883
- username: admin, password: admin
- topic as sensors
- temp,site=room1 value=25

Time Series Admin Client
- http://127.0.0.1:8086 width database name as db
- Leave username and password as blank

Grafana
- Setup influxdb datasource as browser mode
- Leave username and password as blank
- Database set it to db