Run web server `docker-compose up -d` 
&& `docker exec -it integration-messaging-app composer install`
&& `docker exec --user=root -it integration-messaging-app php -S 0.0.0.0:80 -t public`