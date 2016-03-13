# docker-predictionio

## How to build local image
```
git clone -b devel https://github.com/goliasz/docker-predictionio.git
cd docker-predictionio
docker build .
```
## Docker Hub readme
### How to run
```
mkdir $HOME/MyEngine
docker run --hostname pio1 --name pio1 -it -v $HOME/MyEngine:/MyEngine goliasz/docker-predictionio:dev1.6.1 /bin/bash
```

### Inside docker
```
root@pio1:/# pio-start-all
```

### PredictionIO Tutorial
https://docs.prediction.io/demo/tapster/
