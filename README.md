# Docker-For-Data-Science commands
docker build -t punitgavali29/welcome-app .
docker images
docker image rm -f welcome-app
docker run -p 5000:5000 welcome-app
docker tag punitgavali29/welcome-app punitgavali29/welcome-app1
docker login #for docker hub login
docker push punitgavali29/welcome-app:latest
docker compose stop