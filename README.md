# Apache-Docker-Template
Template for creating Docker Web Apps

# To Run

Bind the web app to port 8080

```bash
docker build -t my-apache2 .
docker run -dit --name my-running-app -p 8080:80 my-apache2
```

# Stop Process
```bash
docker ps
```

find the hash of the docker process running

```bash
docker kill <hash>
```

