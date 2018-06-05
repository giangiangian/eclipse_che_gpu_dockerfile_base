# eclipse_che_gpu_dockerfile_base
A base che docker image with nvidia gpu docker support, which can be extended for gpu programming with Eclipse Che

## Instructions
- Install docker-nvidia
- Install eclipse che (multiuser)
- Set default docker runtime as nvidia-docker
- Create stack from docker image, using the image built from this dockerfile
- In terminal, run `nvidia-smi`. If it works, it means that gpu support is enabled. Still, this image does not have any SDK available, therefore it must be extended with some SDK to be useful.