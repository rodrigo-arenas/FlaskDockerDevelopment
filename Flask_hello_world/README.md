# Instructions

### 1. Change to app folder
```
cd Flask_hello_world
```

### 2. Build the image
 * Name it "flask_hello_app"
 * Use any Dockerfile that finds in current directory (.)
```
sudo docker build -t flask_hello_app .
```

### 3. Check the image is created
```
docker images
```

### 4. Run the container
```
sudo docker run -d -p 5000:5000 --name hello-server flask_hello_app
```

### 5. Check the server is running
```
docker ps
```

### 6. Go to localhost
```
[localhost](http://localhost:5000/)
```

### 7. Enter to the container terminal
```
docker exec -it hello-server bash 
```

### 8. Check the container files
```
ls
```

### 9. Exit terminal
```
exit
```

### 10. Stop the container
```
docker stop hello-server
```

