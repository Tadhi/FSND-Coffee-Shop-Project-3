# Full Stack Developer Project 3 -Coffee Shop

> This project was completed as part of the course requirements of Udacity's Full Stack Developer Nanodegree certification. 


The application must:

* Display graphics representing the ratios of ingredients in each drink.
* Allow public users to view drink names and graphics.
* Allow the shop baristas to see the recipe information.
* Allow the shop managers to create new drinks and edit existing drinks.

## Auth0 Account:
> A)- Then update the information in a file auth.py
 ```
AUTH0_DOMAIN = 'fsnd-tota.us.auth0.com' 
ALGORITHMS = ['RS256']
API_AUDIENCE = 'http://localhost:5000'
 ```
> B)- I have created two dummy accounts on my Auth0 profile, both of them are verified and functional.
 
 #### Manager Account
```
eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCIsImtpZCI6IjNxeGd3TzJYRGpqT3o0UzNBZHMyYSJ9.eyJpc3MiOiJodHRwczovL2ZzbmQtdG90YS51cy5hdXRoMC5jb20vIiwic3ViIjoiYXV0aDB8NWVmYmI4OTg3MTQ2OGMwMDEzZmZjMjVmIiwiYXVkIjoiaHR0cDovL2xvY2FsaG9zdDo1MDAwIiwiaWF0IjoxNTkzNTcxNzc3LCJleHAiOjE1OTM1Nzg5NzcsImF6cCI6IndLc0d3TG5jVEhVNDk0VlZkellCUjYyYWJydG9zNFZlIiwic2NvcGUiOiIiLCJwZXJtaXNzaW9ucyI6WyJkZWxldGU6ZHJpbmtzIiwiZ2V0OmRyaW5rcy1kZXRhaWwiLCJwYXRjaDpkcmlua3MiLCJwb3N0OmRyaW5rcyJdfQ.T2oqUS918KGDpiKsoESntIu-6t3lRHuiULT_pGkfpIR0OPtjHX1PrYcfuK5W9LY8IKQESBmJDcOQDkdntNm6IWZZP531sQRmipP3ZDKwhtnMCHUJaljSLhNR5Y1IhusUmQw5ifo-oWj2hWrmEBKecY9aVyqYsQUSh4CLCw6-fhoA2w4QYk6FX6qvxmscQfSh17CuF0YoV-E-uCLz_3TWVtuKhrJu3sY9GPNkauGjarqrqBbhgCmrejELI2A63BIigXt3mWqEveCbtoXjDTLRtQL_kZUN--3TM8aG0NPh0cic-Fl-DBAH3XQnLf6c6JR5GwRsE6hnwBYwC4oH1OI4IQ
```

 #### Barista Account
 ```
 eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCIsImtpZCI6IjNxeGd3TzJYRGpqT3o0UzNBZHMyYSJ9.eyJpc3MiOiJodHRwczovL2ZzbmQtdG90YS51cy5hdXRoMC5jb20vIiwic3ViIjoiYXV0aDB8NWVmYzAzNjhmZDMwZTIwMDEzNjYwZGEzIiwiYXVkIjoiaHR0cDovL2xvY2FsaG9zdDo1MDAwIiwiaWF0IjoxNTkzNTc3MTIyLCJleHAiOjE1OTM1ODQzMjIsImF6cCI6IndLc0d3TG5jVEhVNDk0VlZkellCUjYyYWJydG9zNFZlIiwic2NvcGUiOiIiLCJwZXJtaXNzaW9ucyI6WyJnZXQ6ZHJpbmtzLWRldGFpbCJdfQ.UzoNAkLkmT5Yck7UUxDzkAWSAyux_XX8XnMYPw18_WlbIyoDUMu07QPtL5s-D19U9BbmqOgo5Sthuo1pI2eeRMZZo5EcYwYevkFEOyTyRI7aGnUVigodfLHIim9wMCOsBfsJY0a4yg7kYYvUVqgvlLDjhojV872-kik0UrePYoP7Y-XSHjIn8Rlqegy6KfcEbix_l6d87FHEwrVEHI923zUrDLnjbGQuXP3IUwnH6m3B0tJIe9VORbAZQYL8Lz-FuiBYA61mSvn2EtUN-MhLMojCwjQl-9-ltIpT12HdoFgrRyBzAnT8XSmebTO1t5ikAH3Zjp7LJMmfw80pd9RlzA
 ```
 
 ## POSTman:
 
* Exported collection with configured tokens can be found at: /backend/udacity-fsnd-udaspicelatte.postman_collection_STUDENT_TOKEN.json
* Test results containing 20 successful cases: /backend/udacity-fsnd-udaspicelatte.postman_collection_test_run.json


 ## Backend:
 
* Added Auth0 functionalities on auth.py 
* Implemented RESTful endpoints api.py
* Implemented error handlers 400, 404, 422


## Running the app:
A)- Install dependencies with

```
pip3 install -r backend/requirements.txt
```
B)- Running the server
From within the ./src directory first
```
export FLASK_APP=api.py;
```
C)- To run the server/app, execute
 ```
 flask run --reload
  ```


## Frontend:
* Added the Auth0 variables on environment.ts 
* Guarantee that the frontend can be launched upon an ionic serve command and the login/token retrieval are functional


#### Installing Project dependencies
* This project uses NPM to manage software dependencies. 
* NPM relies on the package.json file located in the frontend directory of this repository. 
* After cloning, open your terminal and run:
```
npm install
```

#### Running Your Frontend in Dev Mode
```
ionic serve
```

## .gitignore:
* enviornment 
* node_modeules
