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
Hello, World!
```

## Acknowledgments
Thats it
