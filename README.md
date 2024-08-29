# zipkin-spring-boot
Implementation of Zipkin-Sleuth in Java SpringBoot

# Zipkin Clients Run 
java -jar target/zipkin-service-1-0.0.1-SNAPSHOT.jar  --server.port=8081

java -jar target/zipkin-service-2-0.0.1-SNAPSHOT.jar  --server.port=8082

java -jar target/zipkin-service-3-0.0.1-SNAPSHOT.jar  --server.port=8083



# Zipkin Server
![alt text](https://github.com/pradneshhhh/zipkin-spring-boot/blob/master/zipkin_server.png)
# Service Flow Map
![alt text](https://github.com/pradneshhhh/zipkin-spring-boot/blob/master/service_map.png)
# Successful Flow
![alt text](https://github.com/pradneshhhh/zipkin-spring-boot/blob/master/green.png)
# Failed Flow
![alt text](https://github.com/pradneshhhh/zipkin-spring-boot/blob/master/red.png)
# Span ID and Trace ID
![alt text](https://github.com/pradneshhhh/zipkin-spring-boot/blob/master/span_id%20trace_id.png)
# Client Exposed Microserivce
![alt text](https://github.com/pradneshhhh/zipkin-spring-boot/blob/master/client_exposed_service.png)
