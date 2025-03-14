# ShuffleNet: An Extremely Efficient Convolutional Neural Network for Mobile Devices
<!-- {ShuffleNet V1} -->

## Introduction

<!-- [ALGORITHM] -->

```latex
@inproceedings{zhang2018shufflenet,
  title={Shufflenet: An extremely efficient convolutional neural network for mobile devices},
  author={Zhang, Xiangyu and Zhou, Xinyu and Lin, Mengxiao and Sun, Jian},
  booktitle={Proceedings of the IEEE conference on computer vision and pattern recognition},
  pages={6848--6856},
  year={2018}
}
```

## Results and models

### ImageNet

|         Model         | Params(M) | Flops(G) | Top-1 (%) | Top-5 (%) | Config | Download |
|:---------------------:|:---------:|:--------:|:---------:|:---------:|:---------:|:--------:|
| ShuffleNetV1 1.0x (group=3)   | 1.87      | 0.146    | 68.13 | 87.81 | [config](https://github.com/open-mmlab/mmclassification/blob/master/configs/shufflenet_v1/shufflenet-v1-1x_16xb64_in1k.py) | [model](https://download.openmmlab.com/mmclassification/v0/shufflenet_v1/shufflenet_v1_batch1024_imagenet_20200804-5d6cec73.pth) &#124; [log](https://download.openmmlab.com/mmclassification/v0/shufflenet_v1/shufflenet_v1_batch1024_imagenet_20200804-5d6cec73.log.json) |
