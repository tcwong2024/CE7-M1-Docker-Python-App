# Sample docker with python application

## Docker run commands :

### 1. build docker
   - docker build -t hello-world-app .

### 2. List all docker images
   - docker images

### 3. run application images
   - docker run -d -p 5000:5000 hello-world-app

### 4. Show the website using CURL
   - curl http://localhost:5000/

### 5. list docker 
   - docker ps
   - docker ps -q
   - docker ps -aq

### 6. Stop the docker
   - docker stop <container id>

### 7. docker system df
   - Show all the container and images in local computer
     
### 8. remove docker with force
   - docker rmi -f <images id>
   - docker container prune
   - docker image prune -a
