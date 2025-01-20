# Deploying a Django TODO Application on EC2, Dockerizing, and Configuring Jenkins
This is a simple notes app built with React and Django.Deploying a Django application on an EC2 instance, Dockerizing it, and configuring Jenkins to automate the deployment process.

## Requirements
1. Python 3.9
2. Node.js
3. React
4. Docker
5. Jenkins

## Installation
1. Clone the repository
```
https://github.com/bhagwati021/Django_Notes_app
```

2. Build the app
```
docker build -t notes-app .
```

3. Run the app
```
docker run -d -p 8000:8000 notes-app:latest
```
