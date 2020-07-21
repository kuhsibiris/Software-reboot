# Software-reboot

This is a list of all commands needed to make a new ubuntu install working for me 

sudo snap install spotify
sudo snap install discord
sudo apt install gdebi
(download zoom from website install with gdebi)


Download CUDA 10.1 from https://developer.nvidia.com/cuda-10.1-download-archive-base

(CC=$(which gcc-8)
Cxx=$(which g++-8)
sudo sh cuda_10.1.105_418.39_linux.run --override
nano ~/.bashrc
  add to file
    export LD_LIBRARY PATH $LD_LIBRARY_PATH /usr/local/cuda/extras/CUPTI/lib64
    export PATH $PATH /usr/local/cuda10.1/bin
    export LD_LIBRARY_PATH $LD_LIBRARY_PATH /usr/local/cuda-10.1/lib64
* sudo apt install docker,io
