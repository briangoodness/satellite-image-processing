# Daytime Satellite Imagery Processing scripts

Helper scripts for downloading satellite imagery and processing for machine learning

Satellite imagery feature extraction and predictions are based on a VGG16 Convolutional Neural Network (CNN) as specified in [Very Deep Convolutional Networks for Large-Scale Image Recognition][1].

## Configuration
- Install Dependencies via Pip: `pip install -r requirements.txt`

## Technology Stack
- Ubuntu 16.04 Server
- Keras w/Tensorflow GPU Backend. See [Keras][2] and [Tensorflow][3] installation instructions.
- [NVIDIA CUDA Toolkit v8.0][4] with [cuDNN v6.0][5] (note: at given time, TF not compatible with more recent versions of CUDA/cuDNN)
- Relied upon the Deep Learning repo from [floydhub][6].

[1]: https://arxiv.org/abs/1409.1556
[2]: https://keras.io/#installation
[3]: https://www.tensorflow.org/install/install_linux
[4]: https://developer.nvidia.com/cuda-toolkit-archive
[5]: https://developer.nvidia.com/rdp/cudnn-download
[6]: https://github.com/floydhub/dl-setup

