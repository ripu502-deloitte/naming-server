# Naming server

- Following dependency needed -> check the pom.xml
- @EnableEurekaServer in public class NamingServerApplication
- application properties -
  -

  	 spring.application.name=naming-server  
  	spring.config.import=optional:configserver:http://localhost:8888  
  	server.port=8761  
  	  
  	eureka.client.register-with-eureka=false  
  	eureka.client.fetch-registry=false
