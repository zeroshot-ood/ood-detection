# Zero-Shot Out-of-Distribution Detection with Feature Correlations
Anonymized Code for openreview submission: https://openreview.net/forum?id=r1g6MCEtwr

## Dependencies
The code is written in Python 2 with Pytorch 1.0. 

## Results
![results](https://github.com/zeroshot-ood/ood-detection/blob/master/results.png)

## Downloading Pre-trained Models
We used pre-trained neural networks open-sourced by [Mahalanobis](https://github.com/pokaxpoka/deep_Mahalanobis_detector/) and  [odin-pytorch](https://github.com/ShiyuLiang/odin-pytroch). The DenseNets trained on CIFAR-10 and CIFAR-100 are by ODIN; remaining are by Mahalanobis:

* [DenseNet on CIFAR-10](https://www.dropbox.com/s/pnbvr16gnpyr1zg/densenet_cifar10.pth?dl=0) / [DenseNet on CIFAR-100](https://www.dropbox.com/s/7ur9qo81u30od36/densenet_cifar100.pth?dl=0) / [DenseNet on SVHN](https://www.dropbox.com/s/9ol1h2tb3xjdpp1/densenet_svhn.pth?dl=0)
* [ResNet on CIFAR-10](https://www.dropbox.com/s/ynidbn7n7ccadog/resnet_cifar10.pth?dl=0) / [ResNet on CIFAR-100](https://www.dropbox.com/s/yzfzf4bwqe4du6w/resnet_cifar100.pth?dl=0) / [ResNet on SVHN](https://www.dropbox.com/s/uvgpgy9pu7s9ps2/resnet_svhn.pth?dl=0)

## Downloading Out-of-Distribtion Datasets
We use download links of three out-of-distribution datasets from [odin-pytorch](https://github.com/facebookresearch/odin):

* [Tiny-ImageNet (resize)](https://www.dropbox.com/s/kp3my3412u5k9rl/Imagenet_resize.tar.gz)
* [LSUN (resize)](https://www.dropbox.com/s/moqh2wh8696c3yl/LSUN_resize.tar.gz)
* [iSUN](https://www.dropbox.com/s/ssz7qxfqae0cca5/iSUN.tar.gz)

