
Image Synthesis from Text using Generative Adversarial Networks (GANs)
----------------------------------------------------------------------


Development & Execution Environment
-----------------------------------

1. Platform - CPU

2. Processor - Intel i3

3. OS - Windows

4. IDE - Anaconda Spyder 

5. Programming Language - Python 3.7

6. Framework - Tensorflow



Folders & Files Description
---------------------------


Folders
-------

1. checkpoint - used to save the trained model

2. dictionary - code files to convert the text captions words to ID and vice versa in GAN implementation

3. train_samples - used to save the generated images from text captions


Files
------

1. model.py - text encoder, generator and discriminator network model code

2. train.py - code to load the Oxford-102 dataset of flowers, train the GAN on the data and test the GAN 

3. train_captions.npy - Oxford-102 dataset of flowers text captions

4. train_images.npy - Oxford-102 dataset of flowers images 

5. utils.py - utility functions used in GAN implementation



Execution Instructions
-----------------------


1. Run the train.py file to train the GAN on the Oxford-102 dataset of flowers and test the GAN to generate images from sample text captions.