# Project Information and Limitations

--------------------------------------------------------------------------------------------------
## INSTRUCTIONS

1. Download the Postman collection from the "resources" package.


--------------------------------------------------------------------------------------------------


# How to connect to DB
--------------------------------------------------------------------------------------------------

#) Go to following url  in the browser :
http://localhost:8080/h2


#) Provide the following details:
Driver Class = org.h2.Driver
JDBC URL  = jdbc:h2:mem:h2db
UserName = sa
Password =




OPEN UI IN BROWSER
-------------------------------------------------------------------------------------------------------------
#) Open the browser in the following url:
http://localhost:8080/



--------------------------------------------------------------------------------------------------

# HOW TO ADD NEW USER USING CURL

curl --location "http://127.0.0.1:8080/api/users" --header "Content-Type: application/json" --data "{\"firstName\": \"Yossi\", \"lastName\": \"Tal\"}"

curl --location "http://127.0.0.1:8080/api/users" --header "Content-Type: application/json" --data "{\"firstName\": \"Dani\", \"lastName\": \"Cohen\"}"

--------------------------------------------------------------------------------------------------

# HOW TO GET EXIST USER USING CURL
curl --location "http://127.0.0.1:8080/api/users/3"



--------------------------------------------------------------------------------------------------

