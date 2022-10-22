# udagram
Udacity Project

Udagram is an Image Filtering Service that was built in the second section of the Udacity CLoud Developer Course. 
The Udagram app was built using the monolith architecture, in this section I will split the application into smaller services.

# Services
## Backend
Api-Feed: This Service contains the api for the user feeds (i.e what the user sees on their timeline), allows users to post photos, and process photos using image filtering
Api-User: This Service contains the logic for user authentication and authorization

## Frontend
Frontend: This Service contains the UI part of the application. It is a basic Ionic client web application that acts as an interface between the user and the backend services

## Reverse Proxy
NGINX Reverse Proxy: This service is for resolving multiple services running on the same port in separate containers. When different backend services are running on the same port, then a reverse proxy server directs client requests to the appropriate backend server and retrieves resources on behalf of the client

## Deployment
This Project was deployed to AWS using EKS
