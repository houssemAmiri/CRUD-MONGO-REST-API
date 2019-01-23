# CRUD-MONGO-REST-API
to test the api 

curl -H "Content-Type: application/json" -X POST -d '{"balance": 100, "name":"checking"}'  "http://localhost:3000/accounts" 

curl -H 'Content-Type: application/json' -X PUT -d '{"balance": 200, "name": "savings"}'  "http://localhost:3000/accounts/{ID}" 

curl "http://localhost:3000/accounts" 

curl -X DELETE "http://localhost:3000/accounts/{ID}" 
Make sure you change the value of {ID} in the PUT and DELETE CURL requests to the value of the
newly created account from the first POST command.
