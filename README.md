# Microservices-CurrencyExchange-CurrencyConversion
This is a repository for a set microservices.

This Repository has 3 microservices.
1. Limits-service to define a minimum and maximum value.
2. Currency-exchange-service to define different countries' currency exchange values to indian rupee value. (Ex: 1USD = 80INR)
3. Currency-conversion-service to convert different countries' currency to indian rupees using the current exchange rate from  Currency-exchange-service. (Ex: 10USD = 10*80 = 800INR)

> Currency-conversion-service and Currency-exchange-service are connected to each other using Spring Cloud Config.
> Eureka Naming Server and Netflix API Gateway are used for load balancing on the microservices and visibity and monitoring.

