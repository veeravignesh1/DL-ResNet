# ResNet

## Team

- [Kunal Bharadwaj](https://github.com/kunalb510) - D19016
- [Pooja More](https://github.com/PoojaMore282) - D19021
- [Veera Vignesh](https://github.com/veeravignesh1) - D19036
- [Vighnes Tamse](https://github.com/vighneshutamse) -D19037
- [DurjayDas](https://github.com/Durjaydas) - D19038

We used  [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) dataset for our experiments with ResNet Architecture. Experiments where conducted with base model as ResNet-18 to tune various parameters and the best hyperparameters where then progressively applied to deeper models. 

[EDA](https://github.com/veeravignesh1/DL-ResNet/blob/master/EDA%20and%20augmentation.ipynb) of the data was done to understand the various class of the image and effect of transformation on the image. 

**Hyper Parameters:**

- Batch Size - 32,64,128,256,512
- Epoch - 10,20,40,60,80
- Optimizer - Adam (with & without weight decay), SGD (with & without momentum and weight decay)
- Transformation - RandomCrop,Random Rotation, Padding, Colorjitter, Normalization
- Learning Rate - Dynamic learning rate

[Experiments](https://github.com/veeravignesh1/DL-ResNet/tree/master/experiments) conducted are available in the folder. Based on the experiments HyperParameters where choosen for further experiments

## Results

|                            Model                             | Accuracy |
| :----------------------------------------------------------: | :------: |
| [ResNet-18](https://github.com/veeravignesh1/DL-ResNet/blob/master/RESNET_18_accuracy_91_07.ipynb) |  91.07%  |
| [ResNet-34](https://github.com/veeravignesh1/DL-ResNet/blob/master/RESNET_34_accuracy_91_96.ipynb) |  91.96   |
| [ResNet-152](https://github.com/veeravignesh1/DL-ResNet/blob/master/experiments/RESNET_151_60_adam_decay.ipynb) |  87.01   |



