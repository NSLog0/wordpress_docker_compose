# wordpress_docker_compose

###This a simple project to run wordpress with docker. So in this project use public image and docker-compose without Dockerfile

#What's inside project 
- mariadb
- wordpress
- corbinu/docker-phpmyadmin

In this project I have linked mariadb data to external docker at data/ and wordpress fil at www/

#How to use 
1. Run 
  ``` 
  $docker-compose up
  ```
  or 
  ``` 
  $docker-compose up -d 
  ```
  for background process, To access your website yourdomain:8080
2. You can access phpmyadmin at yourdomain:8181

