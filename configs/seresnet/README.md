# Squeeze-and-Excitation Networks
<!-- {SE-ResNet} -->

## Introduction

<!-- [ALGORITHM] -->

```latex
@inproceedings{hu2018squeeze,
  title={Squeeze-and-excitation networks},
  author={Hu, Jie and Shen, Li and Sun, Gang},
  booktitle={Proceedings of the IEEE conference on computer vision and pattern recognition},
  pages={7132--7141},
  year={2018}
}
```

## Results and models

### ImageNet

|         Model         | Params(M) | Flops(G) | Top-1 (%) | Top-5 (%) | Config | Download |
|:---------------------:|:---------:|:--------:|:---------:|:---------:|:---------:|:--------:|
| SE-ResNet-50          | 28.09     | 4.13     | 77.74 | 93.84 | [config](https://github.com/open-mmlab/mmclassification/blob/master/configs/seresnet/seresnet50_8xb32_in1k.py) | [model](https://download.openmmlab.com/mmclassification/v0/se-resnet/se-resnet50_batch256_imagenet_20200804-ae206104.pth) &#124; [log](https://download.openmmlab.com/mmclassification/v0/se-resnet/se-resnet50_batch256_imagenet_20200708-657b3c36.log.json) |
| SE-ResNet-101         | 49.33     | 7.86     | 78.26 | 94.07 | [config](https://github.com/open-mmlab/mmclassification/blob/master/configs/seresnet/seresnet101_8xb32_in1k.py) | [model](https://download.openmmlab.com/mmclassification/v0/se-resnet/se-resnet101_batch256_imagenet_20200804-ba5b51d4.pth) &#124; [log](https://download.openmmlab.com/mmclassification/v0/se-resnet/se-resnet101_batch256_imagenet_20200708-038a4d04.log.json) |
