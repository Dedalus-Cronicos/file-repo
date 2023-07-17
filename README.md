This repo saves all the initialization scripts needed for all the components of DC4H which have as database MongoDB.

This is used to test the deployment using another url than the one provided (https://xvalue-deploy.dedalus.eu/x1v1/xds/moduli/).

# Docker image

We have to login to the remote registry

```
docker login cronicosdev.azurecr.io -u __USER__ -p __PASSWORD__
```

where we have to change the fields ****\_\_USER\_\_**** & ****\_\_PASSWORD\_\_****

Then we have to build the image

```
docker build -t cronicosdev.azurecr.io/file-repo:__VERSION__ .
```

where we have to change the field ****\_\_VERSION\_\_**** with the new version of the image.