# spring-cloud-config-server

POC of client microservice of spring-cloud-config-server
- Connect to rabbitmq
- Use spring-cloud-bus
- Use spring-boot-actuator to expose 'busrefresh' to push configuration update to spring-cloud-config-client
- Does not use GIT as repository
- Use profile native with classpath
  - Reference: https://stackoverflow.com/a/54559309
  - spring.cloud.config.server.native.search-locations: '[classpath:/, classpath:/config, classpath:/config/{application}, classpath:/config/{application}/{profile}]'



