# Application Springboot

## Install app
Put movieapi.jar (not provided here) and application.properties in /opt/movieapi/

## Create user
useradd -r -d /opt/movieapi -s /usr/bin/nologin movieapi 

## Install service
Copy movieapi.service in /usr/lib/systemd/system

## Rotation des logs
Copy logrotate config file movieapi dans /etc/logrotate.d/