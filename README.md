# Resturent System (Backend)

Technology Stacks and used for the System 
 -  Java Script(Language)
 -  Node.js
 -  Express.js
 -  NoSQL(MongoDB)
 -  Container(Docker)

## Set up the project 

### 1. Clone the repository:

``` bash
git clone https://github.com/ManulaGunatilleke/restaurant-service.git
```
### 2. Backend navigation:

- Go to inside restaurant-service folder

``` bash
cd restaurant-service 
```

### 3. Install dependencies for backend:

``` bash
npm init 
```
-Note -: install required libraries by using "npm i {Name of the Library}"

### 4. Backend .env file configurations:

- MONGODB_URL = (MONGODB_URL)

### 5. Build Dockerfile for backend:

``` bash
docker build -t restaurant-service .
```
-Note -: You need to install Docker to your Device based on the OS
### Link -: https://docs.docker.com/desktop/
         

### 6. Start backend:

- Go to inside restaurant-service folder
  
``` bash
npm run dev (Option 1)
docker run -d -p 5000:5000 --env-file .env restaurant-service or start using Docker Desktop (Option 2) 
```
### Full Code woth docker-composer.yml -: https://github.com/ManulaGunatilleke/resturent-all.git
