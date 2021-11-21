# currency-conversion-service
Currency Conversion Microservice, part of Udemy Course



URL
https://github.com/hugotb88/currency-conversion-service.gits

#Ports
![image](https://user-images.githubusercontent.com/36638342/142358163-7a35457f-b829-4a58-bbb7-97a92c9fbfa3.png)

#URL
http://localhost:8100/currency-conversion/from/USD/to/INR/quantity/10

#Structure of Response
```
{
    "id": 10001,
    "from": "USD",
    "to": "INR",
    "conversionMultiple": 65.00,
    "quantity": 10,
    "totalCalculatedAmount": 650.00,
    "environment": "8000 instance-id"
}
```

#Diagram
![img.png](img.png)

#Currency Exchange Microservice
URL: https://github.com/hugotb88/currency-exchange-service.git

#Feign Client Implemented to call Currency Exchange Service

# How to Register a microservice in Eureka
- in the POM of the microservice project add the dependency for Eureka client
```
    <dependency>
        <groupId>org.springframework.cloud</groupId>
        <artifactId>spring-cloud-starter-netflix-eureka-client</artifactId>
    </dependency>
```
Additional, just to be sure, you can add the following to the properties file
``eureka.client.serviceUrl.defaultZone = http://localhost:8761/eureka``

![img_1.png](img_1.png)