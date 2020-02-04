# viaai-stack-dockerfiles
Dockerfile for viaai-stack

<b>Notice:</b> You need to install NVIDIA driver before building the Docker image. If you don't know how to install NVIDIA driver, you can follow this command to install VIAAI Stack:
```sh
wget http://archive.via.com.tw/viaai.sh && sudo chmod +x viaai.sh && \
sudo ./viaai.sh && sudo apt-get install viaai-stack
```

For Ubuntu 18.04:
```bash
docker build -f Dockerfile.bionic .
```

For Ubuntu 16.04:
```bash
docker build -f Dockerfile.xenial .
```
