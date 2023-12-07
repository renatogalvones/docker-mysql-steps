# docker-mysql-steps
A simple step by step list to run a docker container with mysql and allow it to be connected via workbench

1. `docker run --name mysql -p 3306:3306 -e MYSQL_ROOT_HOST=% -e MYSQL_ROOT_PASSWORD=test -d mysql/mysql-server:latest`


PS: it was simplier than I tought 😃
The port needs to be explicitly exposed because of security(probably)
