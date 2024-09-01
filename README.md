# Azure-CICD-Deployment



# AZURE-CICD-Deployment-with-Github-Actions

## Save pass:

jVS2tw5ZPXqVtkdLkpgdqBJoB1O7kg1s9lu1HGKBKu+


## Run from terminal:

docker build -t flasksimpleapp.azurecr.io/flask:latest .

docker login flasksimpleapp.azurecr.io

docker push flasksimpleapp.azurecr.io/mltest:latest


## Deployment Steps:

1. Build the Docker image of the Source Code
2. Push the Docker image to Container Registry
3. Launch the Web App Server in Azure 
4. Pull the Docker image from the container registry to Web App server and run 