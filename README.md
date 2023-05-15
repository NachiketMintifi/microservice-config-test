# microservice-config
This repository is an example for config of client-server architecture.


## For client 
add this dependency inside the client side
``` xml
<dependency>
  <groupId>org.springframework.cloud</groupId>
  <artifactId>spring-cloud-starter-config</artifactId>
</dependency>
```
#### Inside the application.properties file of client
```
spring.config.import= configserver:http://ip_address            
spring.profiles.active: dev   #(This is the profile that u want to chose)

```
