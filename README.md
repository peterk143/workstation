# TODO LIST

## build image

## containers.podman.podman_tag

$ podman build -t NAME:TAG dir_storing_Containerfile

## save

### podman_save

$ podman save > workstation_3.4.tar localhost/workstation:v3.4

## compress

$ gzip workstation_3.4.tar > workstation_3.4.tar.gz

## decompress

$ gunzip workstation_3.4.tar.gz

## load

### podman_load

$ podman load -i workstation_3.4.tar  ## find a way to give it a name after loading??

## start container

podman run --name workstation localhost/workstation:v3.4
