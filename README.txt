API Gateway: http://localhost:8765
Forex service: http://localhost:7000, http://localhost:7001
Conversion service: http://localhost:7100
User Mgnt service: http://localhost:7200
Eureka service: http://localhost:8761


Endpoint:
	- http://localhost:8765/currency-conversion-service/currency-converter-feign/from/EUR/to/INR/quantity/11
	- http://localhost:8765/user-mgnt-service/usermgnt/status/check
	
	
	
 Client
   |
   |
   v
API Gateway
   |
   |
   v
