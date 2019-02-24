# docker-openpose

Some attempts to get
[OpenPose](https://github.com/CMU-Perceptual-Computing-Lab/openpose) working
inside a docker container.  Currently this attempt is for CPU only.  

## running

```bash
$ docker run --rm -it --device /dev/video0 -v /tmp/.X11-unix:/tmp/.X11-unix -e DISPLAY gvacaliuc/openpose --help
```
