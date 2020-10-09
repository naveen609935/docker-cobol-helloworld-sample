# docker-cobol-helloworld
Cobol HelloWorld program example with docker.

## Installation
1. Clone this repository and build docker image.
```
$ docker build -t cobol .
```

## Usage
1 . Run OpenCOBOL docker environment.
```
$ docker run -it --rm -w /app cobol bash
```


2 . Run compiled helloworld binary.
```
(docker)$ ./helloworld 
Hello world from COBOL
```

## Acknowledgments
terminal:docker-cobol-helloworld naveen$ docker run -it --rm -w /app cobol bash
root@9f9e7b3f96bb:/app# cd ..
root@9f9e7b3f96bb:/# ./helloworld 
Hello world from COBOL
root@9f9e7b3f96bb:/# 

