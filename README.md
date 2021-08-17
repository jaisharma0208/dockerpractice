# dockerpractice
dockerpractice

https://nodejs.org/en/docs/guides/nodejs-docker-webapp/

docker build . -t jaisharma0208/node-web-app

docker run -p 49160:8080 -d jaisharma0208/node-web-app

docker ps

$ docker logs 0e11cd6668db
Running on http://0.0.0.0:8080

winpty -Xallow-non-tty docker exec -it 0e11cd6668db /bin/bash


curl -i localhost:49160

docker push jaisharma0208/node-web-app
