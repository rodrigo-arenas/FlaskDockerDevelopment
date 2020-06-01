# Instructions

### 1. Change to app folder
```
cd Flask_gunicorn
```

### 2. Build the image
 * Name it "flask_guni_app"
 * Use any Dockerfile that finds in current directory (.)
```
sudo docker build -t flask_guni_app .
```

### 3. Check the image is created
```
docker images
```

### 4. Run the container
```
sudo docker run -p 80:80 --name guni-server flask_guni_app
```

### 5. Check the server is running
```
docker ps
```

### 6. Go to localhost
```
[localhost](http://localhost:80/)
```

### 7. Stop the container
```
docker stop guni-server
```

