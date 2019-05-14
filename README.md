# AngularSpringBootStarter

A minimal Angular and SpringBoot starter project.

To run this project, So into root of the project i.e /AngularSpringBootStarter
and enter following commands

mvn clean install

cd backend/

mvn spring-boot:run





Reference: https://blog.jdriven.com/2016/12/angular2-spring-boot-getting-started/#comment-290737 
https://github.com/jbruinink/ng2boot


Dockerise and run it with below commands

mvn clean install

docker run -it -p 8080:8080 backend:latest
