# Flask REST API - User Management

## Description
A simple REST API built with Flask that supports basic CRUD operations for user data.  
Users are stored in-memory (Python list) for demonstration purposes.

## Endpoints
| Method | Endpoint           | Description          |
|--------|--------------------|----------------------|
| GET    | /users             | Get all users        |
| GET    | /users/<id>        | Get a single user    |
| POST   | /users             | Create a new user    |
| PUT    | /users/<id>        | Update a user        |
| DELETE | /users/<id>        | Delete a user        |

## Installation
Access in Browser or Postman

GET all users: http://127.0.0.1:5000/users

GET single user: http://127.0.0.1:5000/users/1
POST new user:
```bash
pip install flask
bash
POST /users
Content-Type: application/json
{
  "name": "Charlie",
  "email": "charlie@example.com"
}
PUT update user:
PUT /users/1
Content-Type: application/json
{
  "name": "Alice Updated"
}
DELETE user:
DELETE /users/1
