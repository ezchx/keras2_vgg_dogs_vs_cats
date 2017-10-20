# keras2_vgg_dogs_vs_cats

Kaggle's Dogs vs Cats dataset run on the Keras 2 VGG application.

1) Download the training images from Kaggle
2) Save the images in the following directories using the dog_and_cat_image_file_mover notebook:  
   - data/dogscats/train/dogs/ # 11,500 dog images  
   - data/dogscats/train/cats/ # 11,500 cat images  
   - data/dogscats/valid/dogs/ # 1,000 dog images  
   - data/dogscats/valid/cats/ # 1,000 cat images  
3) Run the keras2_vgg_dogs_vs_cats notebook

82s per epoch - 95% training / validation accuracy

- Nvidia 1080ti  
- CUDA 8.0  
- cuDNN 6.0  
- TensorFlow 1.3.0
- Keras 2

https://www.kaggle.com/c/dogs-vs-cats  
https://github.com/fchollet/keras/blob/master/keras/applications/vgg16.py
