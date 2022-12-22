## demo app - developing with Docker

This demo app shows a simple user profile app set up using 
- index.html with pure js and css styles
- nodejs backend with express module
- mongodb for data storage

All components are docker-based

#### To start as K8s pod
    docker login
    docker build -t kington1985/k8s-demo-app:v1.0 .
    docker push kington1985/k8s-demo-app:v1.0