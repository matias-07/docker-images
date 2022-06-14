# PySpark Lab

Simple docker image for PySpark development.

- [Docker Hub Repository](https://hub.docker.com/r/mhuenul/pyspark-lab)

## Build
Execute inside `pyspark-lab` directory:
```
docker build -t pyspark-lab .
```

## Usage
Run the container using your `port` and `workspace` of choice:
```bash
docker container run -it -p $port:8888 -v $workspace:/root/workspace pyspark-lab
```
