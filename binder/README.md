# Binder folder
This folder defines the environment for the repo2docker utility that
auto-creates an docker image for us.

## Build docker image with repo2docker
```
repo2docker --no-run --debug --image-name micmor-ss2019:0.1 .
```

## Start docker image
You may need to adjust the port forwarding depending of any other running images on your machine.
For the moment, we need the following ports:  
- 8888: jupyterlab
- 8787: dask

In the future we might add some more:  
- XXXX: tensorboard (for pytorch/ fastai) 

```
docker run -v /data:/data -p 8888:8888 -p 8787:8787 -p 8786:8786 -it micmor-ss2019:0.1 
```
