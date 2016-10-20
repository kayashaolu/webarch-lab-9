# Lab 9
Create your own API

## In this lab you will accomplish the following
 - Create an API using NodeJS and Express
 - Create a GET and a POST endpoint
 - Use curl to interact with your API
 
 
## Create an API that allows to retrieve and set an integer
 - In your back end API, create a variable called current_value and set it to 0;
 - Create a GET request with path "/value" that returns the current_value variable via JSON
  - There are no inputs for this GET request
  - The output of this GET request should be the count in JSON:
```json
{
  "current_value": 7
}
```
 - Create a POST request with path "/value" that sets the current_value variable via JSON
  - There is a single input called "current_value" that must be sent via JSON
```json
{
  "current_value": 10
}
```
  - There is a single output saying that the command was successful using JSON
```json
{
  "message": "The command was successful"
}
```
