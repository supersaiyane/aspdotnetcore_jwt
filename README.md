# AspdotnetCore_JWt

This project is created in AspDotNet Core 2.1 

purpose of this project is to demonstrate the functioning of JWT and Environemnts like (Prod and Dev)

Sites Useful

https://jwt.io/

https://passwordsgenerator.net/sha256-hash-generator/


postman Request and Response

Request - 1

POST 
http://localhost:5000/api/token

BODY(RAW - Application/json)
{"username":"gurpreet","password":"secret"}

Response -1 
<API TOKEN>


Request -2 
GET
http://localhost:5000/api/values

Headers
Content-Type - application/json
Authorization - Bearer<TOKEN generated in Request 1>

Response -2 
Vaues stored in program

