# Image normalization

ToDo

You run the code [here](https://notebooks.azure.com/Pospa/projects/ml-openhack).

# Environment setup

## Environment

Most of the sample code is Python. To not to mess with any local Python environment, install Anaconda 3.x (miniconda) environment manager. To do that see [miniconda](https://conda.io/en/latest/miniconda.html)

Once you have conda installed localy, you can create ready-to-go environment using [YAML file](keras_tf_cpu.yaml) by running following command.

`conda env create -f keras_tf_cpu.yaml`

for GPU version you have to have CUDA & cuDDN (see below) drivers/SDK

`conda env create -f keras_tf_gpu.yaml`

## Git client

Code samples can be found in this repo. To interact with, you have to have Git client. Installation guide can be found [here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

# Useful links
[TensorFlow GPU support instalation](https://www.tensorflow.org/install/gpu)

