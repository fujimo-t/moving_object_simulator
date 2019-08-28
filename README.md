# Simulator to test moving object detection

The simulator contains:

* A mobile robot with stereo camera
* A mobile robot as a moving object
* Factory like world

Robots is controlled by XBox Controller.

## Requirement

* Docker
* Docker Compose
* NVIDIA GPU
* [NVIDIA Container Toolkit with nvidia-docker2](https://github.com/NVIDIA/nvidia-docker)

## Launch

```shell
$ git clone https://aisl-serv6.aisl.cs.tut.ac.jp:20443/fujimoto/moving_object_simulator.git
$ cd moving_object_simulator/docker
$ xhost +local:root
$ sudo docker-compose up
```
