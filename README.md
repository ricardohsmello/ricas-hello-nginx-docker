# Nginx Docker static page
This is my html hello from Nginx using Docker 

## Built With
- Docker
- Html

## Usage
In Dockerfile directory, run:
```
- docker pull nginx:alpine
```

```
- docker build -t ricas:nginx:latest .
```

```
- docker run -d -p 80:80 ricas-nginx:latest
```
In browser -> localhost:80
