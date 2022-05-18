# GAN_Pokemon_generation
This is a generative adversarial network (GAN) based approach to generate the actors in pokemon artificially.

Generative Adversarial Networks (GANs) are a framework for training networks optimized for generating new realistic samples from a particular representation. In its simplest form, the training process involves two networks. One network, called the generator, generates new data instances, trying to fool the other network, the discriminator, that classifies images as real or fake.

![alt text](https://camo.githubusercontent.com/22afb5278428d6c4c785d1e62639b6dcafc73c7a59b64e86f6d4f71ed54df094/68747470733a2f2f692e696d6775722e636f6d2f4c7765614431732e706e67)

There are broadly 3 categories of GANs:

Unsupervised GANs: The generator network takes random noise as input and produces a photo-realistic image that appears very similar to images that appear in the training dataset. Examples include the original version of GAN, DC-GAN, pg-GAN, etc.

Style-Transfer GANs - Translate images from one domain to another (e.g., from horse to zebra, from sketch to colored images). Examples include CycleGAN and pix2pix.

Conditional GANs - Jointly learn on features along with images to generate images conditioned on those features (e.g., generating an instance of a particular class). Examples includes Conditional GAN, AC-GAN, Stack-GAN, and BigGAN.
