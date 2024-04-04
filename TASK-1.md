# Overview

The task involves setting up a virtual machine running Ubuntu, installing Docker, pulling the hshar/webapp repository, creating a new file within it, and modifying existing files within a Docker container.
After creating and modifying files, the changes should be uploaded to GitHub.

## Tasks To Be Performed:

 1. Install a Docker using VM 
 2. Pull hshar/webapp (https://hub.docker.com/r/hshar/webapp) repository 
 3. Create a new file in this repository

 # Now let's start implementing our solution :-

 ![image](https://github.com/satyamaatmdeep10/Azure-Network/assets/137147966/019dca28-149c-4e03-b6fe-4f55c8ddfa5a)

 ###  Step 1: Setting Up the Virtual Machine

*  Created a virtual machine using Ubuntu as the operating system. 
*  Authentication type: Password. 
* Active ports: 80, 443, and 22.

 ![image](https://github.com/satyamaatmdeep10/Azure-Network/assets/137147966/68da21dc-cfe8-4a8f-87a9-cf2a5ad59e61)

 
 ###Step 2: Connecting to the Ubuntu Linux Machine

*Established a successful connection to the Ubuntu Linux machine using PuTTY, providing the necessary credentials.

![image](https://github.com/satyamaatmdeep10/Azure-Network/assets/137147966/3b15b5d6-1315-4081-92d7-262272214ead)

### Step 3: Installing Docker

*Installed Docker on the Ubuntu machine using the command sudo apt-get install docker.io.
*Verified the installation status with sudo service docker status, ensuring Docker is active and running.

![image](https://github.com/satyamaatmdeep10/Azure-Network/assets/137147966/ca7d604c-5af9-4d38-bdc5-4a8215bedd80)

### Step 4: Pulling the Repository

*Pulled the repository using sudo docker pull hshar/webapp, ensuring that all necessary components are installed on the VM.

![image](https://github.com/satyamaatmdeep10/Azure-Network/assets/137147966/a70143ac-5c75-488c-bd28-11ef5295190c)

### Step 5: Checking Docker Images

*Checked the Docker images using sudo docker image.

![image](https://github.com/satyamaatmdeep10/Azure-Network/assets/137147966/bd7f6eea-af68-4600-97d7-09b980d3d092)

### Step 6: Verifying Container Status

*Confirmed the presence of containers using sudo docker ps -a.

![image](https://github.com/satyamaatmdeep10/Azure-Network/assets/137147966/18c9388c-91f0-4a06-aac9-6d9fb063fbf8)

### Step 7: Creating a Container

*Created a container ID using sudo docker run -itd --name test hshar/webapp and rechecked the container status.

![image](https://github.com/satyamaatmdeep10/Azure-Network/assets/137147966/323f81ef-4da4-47e0-bf69-24e90af606d3)

### Step 8: Modifying Files Inside the Container

*Accessed the container as root user with sudo docker exec -it test bash.
*Navigated to the file directory with cd /var/www/html.
*Removed the existing file with rm index.php.
*Edited and rewrote the file using nano index.html, then exited.







