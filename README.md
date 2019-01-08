# Docker Image for the automated building of an ionic application for android

## Build

docker image build ./ -t dknussmann/ionic:latest

## Run

docker run -i -t dknussmann/ionic:latest

## Exec

docker exec -t -i dknussmann/ionic:latest /bin/bash