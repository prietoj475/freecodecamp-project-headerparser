# FCC API Project: Request Header Parser Microservice

## About
This is my project of the [Request Header Parser Microservice challange](https://www.freecodecamp.org/learn/back-end-development-and-apis/back-end-development-and-apis-projects/request-header-parser-microservice) for the freeCodeCamp Back End Development and APIs certification. It was built based on the boilerplate available [here](https://github.com/freeCodeCamp/boilerplate-project-headerparser/).

## Technologies
- **Node.js** and **Express** to create the server and handle routes, requests and responses.

## Endpoints:

Endpoints | Description | Params
----------|-------------|-------------
GET `/api/whoami` | returns ip address, language, and software information | n/a

#### Example output:
* `{"ipaddress":"159.20.14.100","language":"en-US,en;q=0.5", "software":"Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:50.0) Gecko/20100101 Firefox/50.0"}`

## How to use:
```
npm install
npm start
```
