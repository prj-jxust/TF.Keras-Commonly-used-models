# TF.Keras-常用型号

__自己整理的一些tensorflow下ķeras实现的模型,可在Tensorflow2.0下运行__

## 提示：以下模型均不包含预训练权重的载入，只是模型的实现；不同的卷积模块大部分在分类分割模型中已包含

## 分类模型：
* AlexNet
* Darknet53
* DenseNet
* Dual_path_network
* GoogleNet
* MNasNet
* Resnet34
* Resnet50
* SEResNeXt
* VGG16
* Squeeze_Excite-Network
* MobileNetV3
* Efficientnet

## 分割模型：
* FCN8S
* ICNet
* MiniNetv2
* PSPNet-ResNet50
* RAUNet-3D
* Refinenet
* Segnet
* Unet
* Unet_Xception_Resnetblock
* ResNextFPN
* Deeplabv2
* Deeplabv3+
* FastFCN
* ResUNet-a

### 分割损失函数：
* Focal_Tversky_loss
* C_Focal_loss
* B_Focal_loss
* LovaszSoftmax
* WeightedCCE
* jaccard_loss
* bce_jaccard_loss
* cce_jaccard_loss
* dice_loss
* bce_dice_loss
* cce_dice_loss

### 分割指标：
* iou_score
* jaccard_score
* f1_score
* f2_score
* dice_score

### 新型激活函数：
* gelu
* swish
* mish

### 卷积模块：
* SE
* Res2Net
* Deformable_Conv
