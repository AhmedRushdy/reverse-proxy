## Reverse Proxy
In this project, we will learn how to set up a reverse proxy to forward requests to two microservices using Docker and Docker Compose. The goal is to map specific endpoints to the corresponding microservices, allowing seamless access to different services through a single domain.

### Introduction
A reverse proxy acts as an intermediary between client requests and server responses. It receives incoming requests and forwards them to the appropriate backend services based on predefined rules. In our case, we will configure the reverse proxy to forward requests for specific endpoints to two microservices.

### Example
Here's an example of how the reverse proxy will work:

Requests to <Domain>/service1 will be forwarded to the first microservice.
Requests to <Domain>/service2 will be forwarded to the second microservice.
Prerequisites
Before getting started, make sure you have the following installed on your system:

Docker: Install Docker
Docker Compose: Install Docker Compose
