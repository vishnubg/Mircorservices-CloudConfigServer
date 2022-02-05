# Mircorservices-CloudConfigServer
Example of Microservices Spring Cloud Configuration
To make the application as server you need cloud config dependency 
<dependency>
			<groupId>org.springframework.cloud</groupId>
			<artifactId>spring-cloud-config-server</artifactId>
		</dependency>
and client required cloud starter config dependency
<dependency>
			<groupId>org.springframework.cloud</groupId>
			<artifactId>spring-cloud-starter-config</artifactId>
		</dependency>
Both same time can not be used in same application.
Spring cloud config server should different spring boot
Application.
and client can be your microservices and api gateway to get
Common properties from spring cloud server.
