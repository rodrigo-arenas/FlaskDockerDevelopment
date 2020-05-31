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
 
   * Run image into container

    docker run <image>
 
   * Show all running containers

    docker ps

   * Stop running container
    
    docker stop <container>
    
   * Start container after it was stopped
   
    docker start <container>
    
   * Remove container

    docker rm <container>
    
   * Remove image

    docker rmi <image>
    
   * Remove all container

    docker rm -vf $(docker ps -a -q)

   * Remove all image

    docker rmi -f $(docker images -a -q)



    
</details>