# Kubernetes sample project with API access

The aim of this project with is to create:
- a Deployment with 3 Pods, each containing both a MySQL container and a FastAPI container.
- We'll then need to create a Service and an Ingress to enable access to the API.

Therefore we need to complete the code provided for the API and rebuild the corresponding Docker image (and upload it to DockerHub), so as to enable communication between the API and the database. 

In addition, we need to change the API code to retrieve the database password: datascientest1234. However, this password cannot be hard-coded and must therefore be put in a Secret.

The project includes then: 
- main.py file
- a my-deployment-eval.yml file containing the Deployment declaration
- a my-service-eval.yml file containing the Service declaration
- a my-ingress-eval.yml file containing the Ingress declaration
- a my-secret-eval.yml file containing the Secret declaration
