# docker-mysql

This repo uses docker-compose file to create mysql container.
And in order to provide an UI for mysql it also creates a container for phpmyadmin.
The phpmyadmin ui can be accessed at localhost:8080 

## To start docker-mysql docker container:
1. Clone this repo using 
   - ```git clone <url to this repo>```
2. Build the image 
   - ```docker-compose build```
3. run the container 
   - ```docker-compose up```


### To run mysql UI (phpmyadmin):
Go to localhost:8080 and login using below credentials
- username: myuser
- password: mypassowrd

To login as root, use below credentials
- username: root
- password: password


### To run in Terminal/cmd:

```docker exec -it CONTAINER_ID mysql -uroot -ppassword```

In case you launched my docker container in cmd or terminal from docker `launch in terminal` button then 
use below command to login to mysql: 

```mysql -h localhost -P 3306 -u root -p```


