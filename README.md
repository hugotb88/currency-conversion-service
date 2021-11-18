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