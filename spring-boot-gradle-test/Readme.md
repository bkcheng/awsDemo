docker build -t sbhui/billtest -f src/main/docker/Dockerfile .

$ docker run -p 8002:8002 sbhui/billtest