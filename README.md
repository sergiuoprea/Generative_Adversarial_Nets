# Generative Adversarial Networks (GANs)

Learning about GANs with Ian Goodfellow (Deep Learning Foundation Nanodegree at Udacity)

## What we can do with GANs?

With GANs we are able to generate realistic data, mostly images which are the main focus of generative models. 

### StackGan model

For example, giving a description of a car as model input, it would be able to generate a realistic high-resolution car photo matching that description (totally imaginary). In this case, the GAN is drawing a sample from the probability distribution over all hypothetical images matching the given description. 


### iGAN tool

A tool developed in collaboration between Berkeley and Adobe uses GANs for helping artists. With this tool you will be able to draw realistic images from simple and crude sketches drawed using the mouse. iGAN will search for the nearest possible realistic image.

### Image-to-image translation

An image in one domain can be turned into images in another domain. The most interesting thing about image-to-image translation models is that can be trained in an unsupervised way. 

Facebook trained a model which can turn a realistic image of a human face into a cartoon of a face. Model was trained on photos and cartoons, but it did not need pairs of images showing which photo corresponds to which cartoon.

nVidia showed to use GANs to turn photos of day scenes into photos of night scenes.


#### CycleGAN

Specially good at unsupervised image-to-image translation. This model is able to transform a video of a horse to a video of a zebra. At the same time, the model would change the background looking more like an African grassland. 

We can also use GANs in order to create realistic simulated training sets, or environments to train other machine learning models.
