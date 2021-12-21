# ISAAC-main

To start up the project open a terminal window and go to the rootfolder of this project. Run the following line:

`docker-compose up`

## Ports & services
| Container                 | Address        | Port | Type     | Language/Framework    |
|---------------------------|----------------|------|----------|-----------------------|
| ISAAC-mqtt-server         | localhost:2020 | 2020 | MQTT     | NodeJS                |
| ISAAC-floor-back-end      | localhost:3000 | 3000 | API      | ExpressJS & Sequelize |
| ISAAC-sensor-back-end     | localhost:3001 | 3001 | API      | ExpressJS & Sequelize |
| ISAAC-sensor-log-back-end | localhost:3002 | 3002 | API      | ExpressJS & Sequelize |
| ISAAC-frontend            | localhost:3005 | 3005 | Webapp   | ReactJS               |
| ISAAC-floor-database      | localhost:3306 | 3306 | Database | MySQL                 |
| ISAAC-sensor-database     | localhost:3307 | 3307 | Database | MySQL                 |
| ISAAC-sensor-log-database | localhost:3308 | 3308 | Database | MySQL                 |
