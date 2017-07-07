# GPUEnablerDocker
Docker Files to use GPUEnabler from jupyter/Zeppelin

## Build the juypter image
```
$ git clone https://github.com/iamvuppala/GPUEnablerDocker.git
$ cd GPUEnablerDocker
$ docker build -t <jupyter_image_name> -f Dockerfile.juypter . 
```

## Build the Zeppelin image
```
$ git clone https://github.com/iamvuppala/GPUEnablerDocker.git
$ cd GPUEnablerDocker
$ docker build -t <Zeppelin_image_name> -f Dockerfile.Zeppelin . 
```

## Running juypter image 
```
 $ docker run -it --rm -p 9999:9999 <jupyter_image_name>
```

## Running Zeppelin image
```
 $ docker run -it --rm -p 9999:9999 <Zeppelin_image_name>
```
