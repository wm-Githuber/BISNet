# BISNet

Here, we provide the official pytorch implementation of the paper "BISNet".


# Requirements
* python        3.9.12
* numpy         1.23.1
* pytorch       1.12.1
* torchvision   0.13.1

# Dataset Preparation
## Data Structure
"""  
Change detection data set with pixel-level binary labels;  
├─A  
├─B  
├─label  
└─list  
&emsp;&emsp;├─train.txt  
&emsp;&emsp;├─val.txt  
&emsp;&emsp;├─test.txt  
"""  
A: Images of T1 time  
B: Images of T2 time  
label: label maps  
list: contrains train.txt, val.txt, and test.txt. each fild records the name of image paris (XXX.png).  

## Data Download  
WHU-CD: https://study.rsgis.whu.edu.cn/pages/download/building_dataset.html  
LEVIR-CD: https://justchenhao.github.io/LEVIR/  


# Training and Testing
train.py  
Test.py


# Licence
The code is released for non-commercial and research purposes only. For commercial purposes, please contact the authors.



# Citation
If you find this work interesting in your research, please cite our paper as follow:  
@
