## Build image

docker build . -t blackberry/docker-test

## Run container

docker run -p 80:80 -d --memory="50m" --cpus=2 blackberry/docker-test:latest

### Node app runs at 80 port
