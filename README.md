# TensorNetworkLecture
Numerical exercises for an introductory course to tensor networks.

## Install

### Advanced install
You can compile and install Cytnx from source to get the newest version. Follow the guide in https://cytnx-dev.github.io/Cytnx/1.1.1/adv_install.html

Import cytnx in Python by running
```shell
import sys
sys.path.insert(0,'path/to/Cytnx_lib') # set to where you installed Cytnx
import cytnx
```

### Conda install
Alternatively, you can install the conda package of Cytnx, see https://cytnx-dev.github.io/Cytnx/
However, this version is currently outdated. The programs in this repository might not work on this older build.

Installation with conda:
```shell
conda config --add channels conda-forge
conda create --channel conda-forge --name cytnx python=3.9 _openmp_mutex=*=*_llvm
conda activate cytnx
conda install -c kaihsinwu cytnx
conda install jupyter matplotlib
```

To import:
```shell
import cytnx
```

## Ising model
Run the script `Ising.ipynb` in a python notebook, with the correcte conda environment activated.