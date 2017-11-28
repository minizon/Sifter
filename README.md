# Sifter

## FCN

### U-Net
1. [zhixuhao/unet](https://github.com/zhixuhao/unet) Input512, VGG, 4pooling, Conv after upsamping (subpixel?), simple keras.preprocessing.image.ImageDataGenerator
2. [EdwardTyantov/ultrasound-nerve-segmentation](https://github.com/EdwardTyantov/ultrasound-nerve-segmentation) Inception, ResBlock in skip connection, 4Conv with stride 2 as downsampling, multi outputs, dice loss; train_generator: CustomImageDataGenerator(object), CustomNumpyArrayIterator(Iterator), keras.preprocessing.image.Iterator, (part of) elastic_transform 
3. [raghakot/ultrasound-nerve-segmentation](https://github.com/raghakot/ultrasound-nerve-segmentation) VGG, 4Conv with stride 2 as downsampling, multi outputs; generator: CustomDataGenerator(Iterator), [Using iterators and generators in multi-threaded applications](http://anandology.com/blog/using-iterators-and-generators/)
