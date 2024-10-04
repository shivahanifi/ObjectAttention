# Build and run the docker

```
sudo docker build --build-arg "START_IMG=nvidia/cuda:10.0-cudnn7-devel-ubuntu18.04" --build-arg "release=master" --build-arg "sbtag=Unstable" -t visual_target_attention .

xhost +

sudo nvidia-docker run --rm -it --privileged --gpus all  --privileged -v /dev:/dev -e QT_X11_NO_MITSHM=1 -e DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix --hostname dockerpc --network=host --pid=host visual_target_attention bash
```
