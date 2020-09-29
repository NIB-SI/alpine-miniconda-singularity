# Alpine Miniconda Singularity 

Singularity container with Alpine OS, and miniconda3 installed in /opt/miniconda. 

## Build

    singularity build --fakeroot miniconda.sif Singularity

## Sylabs Container Library

    singularity pull library://cbleker/dev/alpine-miniconda-singularity

## Inspired by:

* [continuumio/miniconda3:4.8.2-alpine](https://hub.docker.com/layers/continuumio/miniconda3/4.8.2-alpine/images/sha256-b9c9f2c7748abdb3291ef2e9b04a8ef3e355f0d7e8030e7a07b8f26c11ed88be?context=explore)
* https://github.com/Docker-Hub-frolvlad/docker-alpine-miniconda3
* https://github.com/show0k/alpine-jupyter-docker
* https://github.com/hpcng/singularity/issues/5075
