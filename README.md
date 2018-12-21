# Sifter

## FCN

### U-Net
1. [zhixuhao/unet](https://github.com/zhixuhao/unet) Input512, VGG, 4pooling, Conv after upsamping (subpixel?), simple keras.preprocessing.image.ImageDataGenerator
2. [EdwardTyantov/ultrasound-nerve-segmentation](https://github.com/EdwardTyantov/ultrasound-nerve-segmentation) Inception, ResBlock in skip connection, 4Conv with stride 2 as downsampling, multi outputs, dice loss; train_generator: CustomImageDataGenerator(object), CustomNumpyArrayIterator(Iterator), keras.preprocessing.image.Iterator, (part of) elastic_transform 
3. [raghakot/ultrasound-nerve-segmentation](https://github.com/raghakot/ultrasound-nerve-segmentation) VGG, 4Conv with stride 2 as downsampling, multi outputs; generator: CustomDataGenerator(Iterator), [Using iterators and generators in multi-threaded applications](http://anandology.com/blog/using-iterators-and-generators/)



## Style Transfer

### examples in keras
1. [keras style transfer](https://github.com/keras-team/keras/blob/master/examples/neural_style_transfer.py)
2. [keras doodle](https://github.com/keras-team/keras/blob/master/examples/neural_doodle.py)
scipy.optimize.fmin_l_bfgs_b  单张图的优化 自定义Evaluator封装K.function
3. [titu1994](https://github.com/titu1994/Neural-Style-Transfer) 单图的优化, color preservation, mask in content and style image
4. [awentzonline/keras-rtst](https://github.com/awentzonline/keras-rtst)
5. [misgod](https://github.com/misgod/fast-neural-style-keras)
layer.add_loss(Regularizer)

### examples in tf
1. [lengstrom fast](https://github.com/lengstrom/fast-style-transfer)

2. [anishathalye](https://github.com/anishathalye/neural-style/)


### examples in torch/pytorch
1. [jcjohnson fast](https://github.com/jcjohnson/fast-neural-style)
2. [NVIDIA](https://github.com/NVIDIA/FastPhotoStyle)
3. [luanfujun](https://github.com/luanfujun/deep-photo-styletransfer)
4. [Yijunmaverick](https://github.com/Yijunmaverick/UniversalStyleTransfer)
可以用mask
5. [CompVis](https://github.com/CompVis/adaptive-style-transfer)
质量较好
6. [xunhuang1995](https://github.com/xunhuang1995/AdaIN-style)
arbitrary style transfer

### reviews
1. [CortexFoundation](https://github.com/CortexFoundation/StyleTransferTrilogy)
