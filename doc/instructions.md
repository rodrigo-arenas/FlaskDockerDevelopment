## Documentation of Docker basics


<details>
  <summary>Glossary</summary>
  
   ### Dockerfile:
    Contains all the instructions under which docker is gonna be build an image. \
    Defines the OS, where to get the code to build the app,etc.
    
   ### Image:
    Blueprint of the instructions expecified in Dockerfil
   ### Container:
    Server under the app is running
</details>


<details>
  <summary>Common Commands</summary>

   * Show all images

    docker images

   * Show all containers

    docker ps -a
 
   * Show all running containers

    docker ps

   * Remove image

    docker rmi <image>

   * Remove container

    docker rm <container>

   * Run image into container

    docker run <image>

   * Stop running container
    
    docker stop <container>
    
   * Start container after it was stopped
   
    docker start <container>
    
</details>