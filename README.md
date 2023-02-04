# Phonebook API Documentation

![Screenshot 2023-02-04 at 9 22 54 AM](https://user-images.githubusercontent.com/57073322/216778300-e302d485-0ff6-49e6-9f5a-f17745f8e91b.png)

This API is a simple phonebook application that allows you to perform basic CRUD operations on a list of people. The API is built using Node.js and the Express library.

# Endpoints
* GET /api/persons: returns a list of all the people in the phonebook
* GET /info: returns a message with the number of people in the phonebook and the current date
* GET /api/persons/:id: returns the details of a person with a given id
* DELETE /api/persons/:id: deletes a person with a given id
* POST /api/persons: creates a new person in the phonebook

# Request Body

For the POST /api/persons endpoint, the request body should include a name and a number field. The name field must be unique.

# Error Responses

* 400 Bad Request: when the request body is missing either the name or number field
* 409 Conflict: when the name field is not unique

# Running the API

1. Clone the repository
2. Run npm install to install the required dependencies
3. Run npm start to start the API server

The API will be running on http://localhost:3001 by default.

# How It's Made
**Tech used:** <img src="https://img.shields.io/badge/-JavaScript-B4E582?logo=javascript&logoColor=F7DF1E&style=flat&labelColor=454545"> <img src="https://img.shields.io/badge/-Express-B4E582?logo=express&logoColor=F7DF1E&style=flat&labelColor=454545"> <img src="https://img.shields.io/badge/-Node.js-B4E582?logo=nodedotjs&logoColor=F7DF1E&style=flat&labelColor=454545">

This is a backend API that allows users to create, read, update, and delete entries in a phonebook. 
