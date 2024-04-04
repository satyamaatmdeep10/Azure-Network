# Overview

 The task entails setting up an Azure Container Registry and connecting it to Docker in a virtual machine, uploading an image to the registry,
 and deploying the image using an app service. This involves creating the registry, committing a container, logging into the registry, pushing 
 the container, creating a web app with Docker, selecting Azure Container Registry as the image source, and hosting the webpage through the app service.

## Tasks To Be Performed: 

1. Create an Azure Container Registry and connect it to Docker running in VM 
2. Upload the image you created in this Azure to container registry 
3. Create an app service to deploy the same image

# Now let's start implementing our solution :-

![image](https://github.com/satyamaatmdeep10/Azure-Network/assets/137147966/dbb1d09f-ced4-4535-8963-97426e74b20b)

### Step 1: Created a container registry successfully.

![image](https://github.com/satyamaatmdeep10/Azure-Network/assets/137147966/33191c48-fd07-453b-b47a-0bc383899bb9)

### Step 2: Created a new container using sudo docker commit test, then committed and named it containernew10.azurecr.io/app. Checked the container with sudo container images.

 ![image](https://github.com/satyamaatmdeep10/Azure-Network/assets/137147966/affb7805-248b-492d-b069-a3481bb16c1b)

 ![image](https://github.com/satyamaatmdeep10/Azure-Network/assets/137147966/d05665bb-f46c-47d5-82fe-321420be1b5b)
 

### Step 3: Logged into the container using the login server with sudo docker login login server, providing username and password.

![image](https://github.com/satyamaatmdeep10/Azure-Network/assets/137147966/51ce30b9-30ce-48ca-924c-da6d3a1d27d7)

![image](https://github.com/satyamaatmdeep10/Azure-Network/assets/137147966/b3e5389f-0c9a-483f-99c1-a125ec671158)


### Step 4: Pushed to the repository using sudo docker push server login server.

![image](https://github.com/satyamaatmdeep10/Azure-Network/assets/137147966/779da2d7-f5e5-47d1-bfdd-a8d636ae5da3)

### Step 5: Created a web app with Docker container as the publish option and Linux as the OS.

![image](https://github.com/satyamaatmdeep10/Azure-Network/assets/137147966/1ecaed22-58cd-453f-a8eb-1e1632667fb1)

### Step 6: Chose Azure Container Registry in Docker for the image source, allowing automatic data retrieval, and successfully created a web app.

![image](https://github.com/satyamaatmdeep10/Azure-Network/assets/137147966/9823386c-3afe-4b32-aa2e-fd533bc67680)

![image](https://github.com/satyamaatmdeep10/Azure-Network/assets/137147966/a8b29743-d7ad-4adb-b983-f45f2d940ced)

### Step 7: Hosted the webpage using the app service by copying the default domain and accessing it through a browser.
