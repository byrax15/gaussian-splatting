FROM nvidia/cuda:11.8.0-devel-ubuntu22.04
LABEL authors="byrax15"

RUN apt-get update && export DEBIAN_FRONTEND=noninteractive
RUN apt-get install -yqq python3 python3-pip ffmpeg openssh-server ninja-build git
RUN pip install plyfile==0.8.1 tqdm 
RUN pip install torch torchaudio torchvision --index-url https://download.pytorch.org/whl/cu118