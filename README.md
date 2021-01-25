![licence:free to use](https://img.shields.io/badge/licence-free--to--use-blue)  [![Linkedin Badge](https://img.shields.io/badge/-gurpreetsingh89-blue?style=flat&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/gurpreetsingh89/)](https://www.linkedin.com/in/gurpreetsingh89/)  [![dev.to Badge](https://img.shields.io/badge/-@gurpreetsingh-000000?style=flat&labelColor=000000&logo=dev.to&link=https://dev.to/gurpreetsingh)](https://dev.to/gurpreetsingh) 

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

