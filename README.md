

MAC: 
docker build buildenv -t my-os-kernel-buildenv  

docker run --rm -it -v $(pwd):/root/env my-os-kernel-buildenv

exit from container

