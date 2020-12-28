# MNIST CNN

### My Setup
```sh
$ sw_vers
ProductName:	Mac OS X
ProductVersion:	10.13.6
BuildVersion:	17G9016

$ conda -V
conda 4.8.3

$ python --version
Python 3.8.5
```

python build in requirements.txt

```
pip install -r requirements.txt
```

### Dataset

MNIST

### Hyperparamaters
```
epochs = 20
batch_size = 1000
lr = .01
momentum = .9
loss = Cross Entropy
```
### Models attempted
1. Max pool
1. Average pool
1. Max pool / Wide FCs
1. Max pool / Wide FCs / Deep Conv

#### Best Accuracy Model: 4 (max_wide_deep)

### Accuracy Achieved
train/test >98%
