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
```bash
pip install flask
