# TCCM-DL-2022

**TCCM school** - Multiscale, Machine Learning and QSAR methods applied to biomolecules:\
_Introduction to Deep Learning, Tensorflow/Keras and Convolutional neural network_

# How to download slides and hands-on

```
git clone https://github.com/so07/TCCM-DL-2022.git
```

# How to install requirements

## Tensorflow

- [How to install Tensorflow with pip](https://www.tensorflow.org/install/pip)
- [How to install Tensorflow with conda](https://docs.anaconda.com/anaconda/user-guide/tasks/tensorflow/)

## Jupyter software

- [How to install Jupyter notebook](https://jupyter.org/install)

# How to run notebooks

```
cd TCCM-DL-2022
jupyter notebooks
```

## How to run notebooks on a cluster

open a ssh tunnel from local machine to compute node

```
ssh -L 9999:localhost:9999 LOGIN_NODE ssh -L 9999:localhost:9999 COMPUTE_NODE
```

run notebook on the compute node

```
cd TCCM-DL-2022
jupyter notebook --port=9999 --no-browser
```

