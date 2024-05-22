# Agnostic Sharpness-Aware Minimization
This is the official implementation of AgnosticSAM

## Environment
USing Annaconda to install  
`conda env create -f agnosticSAM.yml`

## Dataset
Create a folder `../dataset` to save downloaded dataset

## Training model
We provide some training log in folder `log_files`.
  
Here, we provide the script to reproduce our results in the paper for CIFAR100 dataset. For CIFAR10 dataset, please change `rho` and `rho_lst` following setting in the paper.



### Acknowledgement
This repository is based on [SAM](https://github.com/davda54/sam) and [OT-MDR](https://github.com/anh-ntv/OT_MDR)

