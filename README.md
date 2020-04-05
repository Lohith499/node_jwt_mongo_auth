# node_jwt_mongo_auth

## Features
1. Register
2. Login
3. Protected API

#### Database Used : MongoDB
#### Authentication done using JWT
#### Registration : Username and Password(Encrypted using Bcrypt)
#### API : built using ExpressJs

#### This App gives us overview of how we can use JWT to maintain Authentication as middleware before giving access to any of the API

## Libraries used

1. mongoose - to connect and do crud operations on MongoDB collection
2. jsonwebtoken - to maintain authentication 
3. body-parser - to extract data from request
4. bcrypt - to encrypt and decrypt the password
5. express - Framework to develop APIs 
6. dotenv - helps us extracting vcalues from .env file
