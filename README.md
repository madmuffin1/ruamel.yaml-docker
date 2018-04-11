# ruamel.yaml-docker

![build status](https://img.shields.io/docker/build/finodigital/ruamel-yaml.svg) ![automated build](https://img.shields.io/docker/automated/finodigital/ruamel-yaml.svg)

This repo contains a Dockerfile which is automatically built and available at https://hub.docker.com/r/finodigital/ruamel-yaml/. 

The image contains
 - [Python 2.7 on Alpine Linux](https://hub.docker.com/_/python/)
 - The pip modules [ruamel.yaml](https://pypi.python.org/pypi/ruamel.yaml) and [ruamel.ordereddict](https://pypi.python.org/pypi/ruamel.ordereddict)
 
That's all there is.

### Why?

Installing ruamel modules is somewhat time consuming, since they contain native code which needs to be compiled. By using this image, I sped up a build process step that needed the modules available by a little less than 1 minute per execution.

### Contributions?

Are welcome, but keep in mind that the scope of this image is very limited, other packages should not be added.
