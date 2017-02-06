# TensorFlow Practice

## Resources
- [MNIST For ML Beginners](https://www.tensorflow.org/tutorials/mnist/beginners/)

## Installation
- Install [Python 3.5](https://www.python.org/downloads/release/python-352/)
- Install TensorFlow via pip
```
pip install --upgrade https://storage.googleapis.com/tensorflow/windows/gpu/tensorflow_gpu-0.12.1-cp35-cp35m-win_amd64.whl
```
- Install [Cuda Toolkit](https://developer.nvidia.com/cuda-downloads)
- Install [cuDNN](https://developer.nvidia.com/cudnn) into the toolkit home directory
- Set the Environment Variables
```
CUDA_HOME=C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v8.0

#not sure about this...seemed to work fine without the variabls...weird huh
LD_LIBRARY_PATH=C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v8.0\lib
DYLD_LIBRARY_PATH=C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v8.0\lib
```