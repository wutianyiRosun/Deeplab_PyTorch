# Deeplab_Pytorch
An implementation of DeepLab: Semantic Image Segmentation with Deep Convolutional Nets, Atrous Convolution, and Fully Connected CRFs

# Performance
  - Performance in mean IoU on VOC 12 val set (iteration: 20k, single-scale input for training)
  
| input            |   Deeplab_Pytorch   |
| ----------------:| -------------------:| 
| x1               |  72.05%             | 
| x(1,0.5, 0.75)   |  73.00%             | 


note:
using batchsize=10


## Acknowledgment
This code is heavily borrowed from [Pytorch-Deeplab](https://github.com/speedinghzl/Pytorch-Deeplab).
