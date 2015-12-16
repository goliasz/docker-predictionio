# docker-predictionio
PredictionIO docker container
## How to build local image
git clone https://github.com/goliasz/docker-predictionio.git<br>
cd docker-predictionio<br>
docker build .<br>

## Docker Hub readme
### How to run
docker run --hostname pio1 --name pio1 -it -p 8000:8000 -p 7070:7070 -p 7071:7071 -p 7072:7072 -v $HOME/MyEngine:/MyEngine goliasz/docker-predictionio /bin/bash

### Inside docker
root@pio1:/# pio-start-all

### PredictionIO Tutorial
https://docs.prediction.io/demo/tapster/


This docker setup is based on "sphereio/docker-predictionio".

