## 3d-webapp

A basic 3D static webapp deployed on Kubernetes cluster. The app has multiple endpoints which you can play with. The app is deployed on a Kubernetes cluster and is accessible via a LoadBalancer service.

### Endpoints:
* `/` - The main page
* `/health` - Health check endpoint
* `/score` - Endpoint which takes JSON input and returns the score JSON
* `/docs` - Micro doc page
* `/meta` - Meta data of the app

### How to run:
* Clone the repo
* ```sh
  docker build --tag risikeshops/ml-score-api .
