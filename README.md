server:
  port: 9191
spring:
  h2:
    console:
      enabled: true

  application:
    name: PAYMENT-SERVICE      

      
eureka:
  client:
    register-with-eureka: true
    fetch-registry: true
    service-url:
      defaultZone: http://localhost:8761/eureka/

  instance:
    hostname: localhost
