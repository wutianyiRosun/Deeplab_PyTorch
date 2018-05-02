# Deeplab_Pytorch
An implementation of DeepLab: Semantic Image Segmentation with Deep Convolutional Nets, Atrous Convolution, and Fully Connected CRFs


### Train

You can download pretrianed model on COCO [here](https://pan.baidu.com/s/1cnpQ9ayuH6j7qW2yJOK52g). 

```
python train.py
```

# Performance
  - Performance in mean IoU on VOC 12 val set (iteration: 20k, single-scale input for training)
  
| input            |   Deeplab_Pytorch   |
| ----------------:| -------------------:| 
| x1               |  72.05%             | 
| x(1, 3/4, 1/2)   |  73.00%             | 


note:
using batchsize=10


## Acknowledgment
This code is heavily borrowed from [Pytorch-Deeplab](https://github.com/speedinghzl/Pytorch-Deeplab).
