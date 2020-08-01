# Full Stack Developer Project 3 -Coffee Shop

> This project was completed as part of the course requirements of Udacity's Full Stack Developer Nanodegree certification. 


## 1) Auth0 account:
> A)- Then update the information in a file auth.py
 ```
AUTH0_DOMAIN = 'fsnd-tota.us.auth0.com' 
ALGORITHMS = ['RS256']
API_AUDIENCE = 'http://localhost:5000'
 ```
> B)- I have created two dummy accounts on my Auth0 profile, both of them are verified and functional.
 
 #### Manager Account:
 
 #### Barista Account:
 
## Tasks

There are `@TODO` comments throughout the project. We recommend tackling the sections in order. Start by reading the READMEs in:

1. [`./backend/`](./backend/README.md)
2. [`./frontend/`](./frontend/README.md)

## About the Stack

We started the full stack application for you. It is desiged with some key functional areas:

### Backend

The `./backend` directory contains a partially completed Flask server with a pre-written SQLAlchemy module to simplify your data needs. You will need to complete the required endpoints, configure, and integrate Auth0 for authentication.

[View the README.md within ./backend for more details.](./backend/README.md)

### Frontend

The `./frontend` directory contains a complete Ionic frontend to consume the data from the Flask server. You will only need to update the environment variables found within (./frontend/src/environment/environment.ts) to reflect the Auth0 configuration details set up for the backend app. 

[View the README.md within ./frontend for more details.](./frontend/README.md)
