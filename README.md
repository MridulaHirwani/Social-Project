# Introduction
Project **Social-Project** is an api developed using Django and python and connected to Mongo DB .
These docs describe how to use the project API.

## Status Codes
Project returns the following status codes in its API:

| Status Code | Description |
| ----------- | ------------|
| 200 | **OK** |
| 201 | **CREATED** |
| 400 | **BAD REQUEST** |
| 404 | **NOT FOUND** |
| 500 | **INTERNAL SERVER ERROR** |

## URL Paths

### Users 
The below  are the path to access the users model :
| Method | Path | Description |
|------- |----|-------------|
| **GET** | */api/users* | To retrive all the users data |
| **POST** | */api/users* | To add all the users data |
| **PUT** | */api/users* | To update all the users data |
| **DELETE** | */api/users/:id* | To delete user data of given id|

### Posts
The below  are the path to access the posts model :
| Method | Path | Description |
|------- |----|-------------|
| **GET** | */api/posts* | To retrive all the posts |
| **POST** | */api/posts* | To add all the posts |
| **PUT** | */api/posts* | To update all the posts |
| **DELETE** | */api/posts/:id* | To delete user data of given post|

### Login
The below  are the path to access the users model :
| Method | Path | Description |
|------- |----|-------------|
| **GET** | */api/login/:phone-number* | To retrive the user data |

### Follow
The below  are the path to access the follow model :
| Method | Path | Description |
|------- |----|-------------|
| **GET** | */api/follow* | To retrive all the follow requests |
| **POST** | */api/follow* | To add all the follow requests |
| **PUT** | */api/follow* | To update all the follow requests |
| **DELETE** | */api/follow* | To delete user data of given follow requests |

### How to install django project
1. Create a Python virtualenv
2. install pip install Social-Project
3. Run : python manage.py runserver

