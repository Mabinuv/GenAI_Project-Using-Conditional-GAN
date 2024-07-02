# Gen_AI

This project will develop a Conditional Generative adversarial network (cGAN).

A generator tries to fool the discriminator and create realistic images while the discriminator figures out if the image is real or fake. A GAN network is very suitable when there is no clear pattern or we want to "create" new data samples. A generator creates new and realistic images from images, but in this project, we utilize Conditional GAN that takes additional data and conditions the fake data generation process to generate a particular type of fake data.

This can according to google crash course summarise as:

![GAN!]{https://github.com/Mabinuv/GenAI_Proj---Using-Conditional-GAN/blob/main/gan_diagram.svg}


The generator learns to generate plausible data. The generated instances become negative training examples for the discriminator.
The discriminator learns to distinguish the generator's fake data from real data. The discriminator penalizes the generator for producing implausible results.
The setup is further visualised below for the generator and discriminator provided from google crash course:GAN

Some helpful reading materials:

https://dl.acm.org/doi/abs/10.1145/3422622
https://arxiv.org/abs/1411.1784
https://arxiv.org/abs/1611.07004
Task
For this task we will use FlyingObject Dataset. Given the very first frame of a sequence, generate the last frame.

TODO: Implement a cGAN.

TODO: Condition the generation process such that given the first image of the sequence, the cGAN will generate the last frame. Follow the instructions on Blackboard.

TODO: Select a good metric to evaluate the models performance and argue in presentation why does the metric give a good overview of the performance.

Question: Explain in the presentation what you did and why. Present a pipeline of the code.

Note: The current image resolution is set to 32x32 (i.e. IMAGE_WIDTH and IMAGE_HEIGHT) in config.py. This way initial experiements can run faster. Once you implement the inital version of the network, please set the resolution values back to 128x128. Experimental results should be presented for this high resolution images.
