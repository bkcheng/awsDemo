docker build -t sbhui/bentestdb -f src/main/docker/Dockerfile .

$ docker run -p 8001:8080 sbhui/bentestdb