# Django React Iot Dashboard

A simple proof-of-concept application which can store sensor data (eg. temperature sensor data) coming on a POST endpoint, expose the stored data on a GET endpoint
as well as using WebSocket .

Has a Frontend Application developed in React Js which can display to the enduser, stored sensor data as well as a graph of the stored data.

>>Application is Developed with 
- Django
- Django REST Framework
- Channals (for WebSocket)
- React Js

>> Screenshot 
![alt text](https://raw.githubusercontent.com/viratayya/DjangoReactIotDashboard/master/screenshot/Capture.PNG)

>>Pre-requirements 
- Docker
- Node.js 

>>To run application \
- $docker-compose up --build
- go to http://localhost:8000

>>Docker Container details (Development SetUp)
- basicpython (Django)
  - port 8000
- basicmysql (Database)
  - port 8306
- redis
  - port 6379
  
