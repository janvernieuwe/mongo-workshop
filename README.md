# MongoDB workshop
## Start the mongodb docker image
Start up docker image with the mongodb server.
```shell script
docker-compose up
```
## Install robomongo
[Download](https://robomongo.org/download) robo mongo here, select the right program and operating system.

Add a new connection to the mongodb container
```shell script
Name: workshop
Address: localhost
Port: 27016
```
## Useful links
* https://docs.mongodb.com/manual/tutorial/update-documents/
* https://raw.githubusercontent.com/ozlerhakan/mongodb-json-files/master/datasets/restaurant.json
