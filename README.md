# Full Stack Developer Project 3 -Coffee Shop

> This project was completed as part of the course requirements of Udacity's Full Stack Developer Nanodegree certification. 


## 1) Auth0 Account
> A)- Then update the information in a file auth.py
 ```
AUTH0_DOMAIN = 'fsnd-tota.us.auth0.com' 
ALGORITHMS = ['RS256']
API_AUDIENCE = 'http://localhost:5000'
 ```
> B)- I have created two dummy accounts on my Auth0 profile, both of them are verified and functional.
 
 #### Manager Account:
```
eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCIsImtpZCI6IjNxeGd3TzJYRGpqT3o0UzNBZHMyYSJ9.eyJpc3MiOiJodHRwczovL2ZzbmQtdG90YS51cy5hdXRoMC5jb20vIiwic3ViIjoiYXV0aDB8NWVmYmI4OTg3MTQ2OGMwMDEzZmZjMjVmIiwiYXVkIjoiaHR0cDovL2xvY2FsaG9zdDo1MDAwIiwiaWF0IjoxNTkzNTcxNzc3LCJleHAiOjE1OTM1Nzg5NzcsImF6cCI6IndLc0d3TG5jVEhVNDk0VlZkellCUjYyYWJydG9zNFZlIiwic2NvcGUiOiIiLCJwZXJtaXNzaW9ucyI6WyJkZWxldGU6ZHJpbmtzIiwiZ2V0OmRyaW5rcy1kZXRhaWwiLCJwYXRjaDpkcmlua3MiLCJwb3N0OmRyaW5rcyJdfQ.T2oqUS918KGDpiKsoESntIu-6t3lRHuiULT_pGkfpIR0OPtjHX1PrYcfuK5W9LY8IKQESBmJDcOQDkdntNm6IWZZP531sQRmipP3ZDKwhtnMCHUJaljSLhNR5Y1IhusUmQw5ifo-oWj2hWrmEBKecY9aVyqYsQUSh4CLCw6-fhoA2w4QYk6FX6qvxmscQfSh17CuF0YoV-E-uCLz_3TWVtuKhrJu3sY9GPNkauGjarqrqBbhgCmrejELI2A63BIigXt3mWqEveCbtoXjDTLRtQL_kZUN--3TM8aG0NPh0cic-Fl-DBAH3XQnLf6c6JR5GwRsE6hnwBYwC4oH1OI4IQ
```

 #### Barista Account:
 ```
 eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCIsImtpZCI6IjNxeGd3TzJYRGpqT3o0UzNBZHMyYSJ9.eyJpc3MiOiJodHRwczovL2ZzbmQtdG90YS51cy5hdXRoMC5jb20vIiwic3ViIjoiYXV0aDB8NWVmYzAzNjhmZDMwZTIwMDEzNjYwZGEzIiwiYXVkIjoiaHR0cDovL2xvY2FsaG9zdDo1MDAwIiwiaWF0IjoxNTkzNTc3MTIyLCJleHAiOjE1OTM1ODQzMjIsImF6cCI6IndLc0d3TG5jVEhVNDk0VlZkellCUjYyYWJydG9zNFZlIiwic2NvcGUiOiIiLCJwZXJtaXNzaW9ucyI6WyJnZXQ6ZHJpbmtzLWRldGFpbCJdfQ.UzoNAkLkmT5Yck7UUxDzkAWSAyux_XX8XnMYPw18_WlbIyoDUMu07QPtL5s-D19U9BbmqOgo5Sthuo1pI2eeRMZZo5EcYwYevkFEOyTyRI7aGnUVigodfLHIim9wMCOsBfsJY0a4yg7kYYvUVqgvlLDjhojV872-kik0UrePYoP7Y-XSHjIn8Rlqegy6KfcEbix_l6d87FHEwrVEHI923zUrDLnjbGQuXP3IUwnH6m3B0tJIe9VORbAZQYL8Lz-FuiBYA61mSvn2EtUN-MhLMojCwjQl-9-ltIpT12HdoFgrRyBzAnT8XSmebTO1t5ikAH3Zjp7LJMmfw80pd9RlzA
 ```
 
 ## 2) POSTman
 
* Exported collection with configured tokens can be found at: /backend/udacity-fsnd-udaspicelatte.postman_collection_STUDENT_TOKEN.json
* Test results containing 20 successful cases: /backend/udacity-fsnd-udaspicelatte.postman_collection_test_run.json


 ## 3) Backend
 
* Added Auth0 functionalities on auth.py 
* Implemented RESTful endpoints api.py
* Implemented error handlers 400, 404, 422


## 4) Running the app
A)- Install dependencies with:

```
pip3 install -r backend/requirements.txt
```
  
   ```
    ```
    
     ```
      ```

 
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
