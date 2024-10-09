<!-- docker-compose build
docker-compose up (activate - local)
docker-compose down (shut down - local)

docker tag runpod-worker-template muhammadusman1706/serverless-runpod-docker-app:latest

docker push muhammadusman1706/serverless-runpod-docker-app:latest -->


docker build --platform linux/amd64 --tag muhammadusman1706/serverless-runpod-docker-app:latest .
docker push muhammadusman1706/serverless-runpod-docker-app:latest