# CTMixer

## Convolution Transformer Mixer for Hyperspectral Image Classification (CTMixer)
The paper titled "**Convolution Transformer Mixer for Hyperspectral Image Classification**" has been accepted by GRSL in Sep 2022, which is an official implementation for **CTMixer**.

## Pytorch
Torch: 1.7.0

Python: 3.7.3
 
## Model
Learning Rate: 0.001

Epoch: 100

Batch Size: 100

Patch Size: $11\times11$

Encoder Layer: 1

Attention Header: 4

Optimizer: Adam (weight_decay=1e-4)

Scheduler: CosineAnnealingLR

# Paper

[Convolution transformer mixer for hyperspectral image classification](https://ieeexplore.ieee.org/document/9903640)

If you find this code to be useful for your research, please consider citing.

```
@article{zhang2023convolution,
  author={Zhang, Junjie and Meng, Zhe and Zhao, Feng and Liu, Hanqiang and Chang, Zhenhui},
  journal={IEEE Geoscience and Remote Sensing Letters}, 
  title={Convolution transformer mixer for hyperspectral image classification}, 
  year={2023},
  volume={},
  number={},
  pages={1--5},
  doi={10.1109/LGRS.2022.3208935}}
```

## Other

If you encounter any problems reproducing the code, please do not hesitate to contact us.

E-mail: junjiezhang98@yeah.net
