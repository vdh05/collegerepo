# 22IT037 DEVOPS PRACTICAL-4
Packaging Application Using Docker - 1
 Clone any node or react project from github and package the app using docker.


Step 1:
Clone the Repository First, clone the reactfolio repository to your local machine using the following command:
 ![image](https://github.com/user-attachments/assets/bc266031-0204-4968-8ef6-c8ab28e7e3e4)



Step 2:
Navigate to the Repository Directory Navigate to the cloned repository directory:
 ![image](https://github.com/user-attachments/assets/e18b15a1-f533-4530-bae4-8cb4a2703b8e)



Step 3:
Create a Dockerfile Create a Dockerfile in the root directory of the repository. Open your favorite text editor and create a file named Dockerfile with the following contents:
 

Step 4:
Build the Docker Image Next, build the Docker image using the following command:
 


Step 5:
Verify the Docker Image Verify that the Docker image was successfully built by listing all Docker images:
 

Step 6:
Log in to Docker Hub Log in to your Docker Hub account using the following command:
 


Step 7:
Tag the Docker Image Tag the Docker image with your Docker Hub username and repository name:


 


Step 8:
Push the Docker Image to Docker Hub Finally, push the Docker image to your Docker Hub account:
 

Step 9:
Verify the Pushed Image Log in to your Docker Hub account through the web interface and navigate to the Repositories tab. You should see your reactfolio repository listed with the latest tag.

 
Step 10:
Running dockerHub image as Container
 

 


 

 

