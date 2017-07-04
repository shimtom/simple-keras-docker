# Simple Keras Docker

Tensorflow + Keras用のDockerイメージ.
サポートしているpythonのバージョンは3系のみ.


## Install
### CPU version
```
$ docker run -it -p 6666:6666 shimtom/simple-keras-docker
```

### GPU version
```
$ nvidia-docker run shimtom/simple-keras-docker:
```
> Note: need to install [NVIDIA Docker](https://github.com/NVIDIA/nvidia-docker)

### Option Port
* `6666`: for TensorBoard
