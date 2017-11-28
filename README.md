## What does this repo contain?

This is an example of a Neural Network of the Deep Convolutional GAN type.  
The neural net has been trained on the CelebA set of images containing 
celebrity faces: 

http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html

## What does the neural net do?

The purpose of this network is to generate images of faces  
that closely resemble real photos.  

https://github.com/SirObi/gan-face-generation/blob/master/dlnd_face_generation.ipynb  
(scroll to the bottom of the Jupyter notebook to see results)

## What does this GAN consist of?  

Deep Convolutional GANs (DCGANs) essentially consist of two  
neural nets: the generator and discriminator.  

The generator tries to create an image closely resembling a real  
photograph.  
The discriminator learns to tell apart the generated images from  
real images and provides the generator with feedback.

In this way, both networks are able to train each other.  
The goal is to train the generator to the point where the  
discriminator will consistently fail to make the correct guess
in 50% of the cases.



