# Springboot-Project

#Curl for creating employees in database

curl --location --request POST 'localhost:8080/api/employees' \
--header 'Content-Type: application/json' \
--data-raw '{
    "firstName": "Pratibha",
    "lastName": "kumari",
    "email": "abc21"
}'

