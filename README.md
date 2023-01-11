# Intro-Deep-Learning-Week-5

Artists are distinguished by their distinctive styles, such as the use of color and brushwork. With the advent of generative adversarial networks (GANs), the unique qualities of artists like Claude Monet can now be replicated through algorithms.

A GAN is composed of at least two neural networks, the generator and the discriminator. The generator network generates the images, and in this competition, you are tasked with creating images in the style of Monet. The generator is trained using the discriminator network.

The two networks work in opposition, with the generator attempting to deceive the discriminator and the discriminator striving to correctly identify real vs. generated images.

The objective of this project is to develop a GAN that can produce between 7,000 and 10,000 images that emulate Monet's style.

As per the directive of the project, this notebook is based on the Kaggle starter project: Monet Painting Dataset (New) : https://www.kaggle.com/competitions/gan-getting-started

This notebook utilizes a CycleGAN architecture to add Monet-style to photos. For this project, we will be using the TFRecord dataset. Import the following packages and change the accelerator to TPU.

For more information, check out TensorFlow and Keras CycleGAN documentation pages.

The dataset contains four directories: monet_tfrec, photo_tfrec, monet_jpg, and photo_jpg. The monet_tfrec and monet_jpg directories contain the same painting images, and the photo_tfrec and photo_jpg directories contain the same photos.

The monet directories contain Monet paintings. Use these images to train your model.

The photo directories contain photos. Add Monet-style to these images and submit your generated jpeg images as a zip file. Other photos outside of this dataset can be transformed but keep your submission file limited to 10,000 images.

monet_jpg - 300 Monet paintings sized 256x256 in JPEG format

monet_tfrec - 300 Monet paintings sized 256x256 in TFRecord format

photo_jpg - 7028 photos sized 256x256 in JPEG format

photo_tfrec - 7028 photos sized 256x256 in TFRecord format
