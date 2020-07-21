# Software-reboot

This is a list of all commands needed to make a new ubuntu install working for me 
install 18.04 (minimun install no privative software)

intall docker.io
set user in docker group (see web)

sudo apt install nvidia-435
nvidia docker https://github.com/NVIDIA/nvidia-docker
docker run --gpus all -it -p 8888:8888 tensorflow/tensorflow:latest-gpu-jupyter 
