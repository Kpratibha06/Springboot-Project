# Springboot-Project

## Curl for creating employees in database.

`curl --location --request POST 'localhost:8080/api/employees' \
--header 'Content-Type: application/json' \
--data-raw '{
    "firstName": "Pratibha",
    "lastName": "kumari",
    "email": "abc21"
}'`


## Curl for getting employees list in database

`curl --location --request GET 'localhost:8080/api/employees'`


## Curl for getting employees list by ID in database

`curl --location --request GET 'localhost:8080/api/employees/2'`


## Curl for updating employees by ID in database

`curl --location --request PUT 'localhost:8080/api/employees/2' \
--header 'Content-Type: application/json' \
--data-raw '{
    "firstName": "Pranesh",
    "lastName": "k",
    "email": "abc21"
}'`


## Curl for deleting employees by ID in database.

`curl --location --request DELETE 'localhost:8080/api/employees/3'`
