### Prerequisites

- Docker
- Docker Compose
- Access to SloaneLab Docker Hub account

1. **Download the Docker Compose file**
   
   curl -O https://github.com/sloanelab-org/knowledgebase-portals/blob/main/docker-compose.yml
   
3. **Navigate to the directory**
   
    cd your/local/directory

5. **Log in to SloaneLab Docker Hub account**
   
    docker login

7. **Run the KnowledgeBase portal in attached mode (which allows you to see the output in the terminal)**
   
    docker-compose up

   Note: The first time you run this command, it will take some time to download and pull all necessary images from Docker Hub.
   Subsequent runs will be faster as the images will be cached locally.

   After the application has started, the KnowledgeBase portal will be available at: http://localhost:10220

9. **Run the KnowledgeBase portal in detached mode (which runs the services in the background)**

   docker-compose up -d

10. **Stop the application running in detached mode**

    docker-compose down



   For a demonstration of how to run the application, please watch the demo video: [Watch Demo] (https://www.youtube.com/@SloaneLab/videos)

   For any questions, or if you need access to the SloaneLab Docker Hub credentials, please contact us at sloanelab@ucl.ac.uk
 
