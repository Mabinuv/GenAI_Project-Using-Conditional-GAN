# Gen_AI

This project will develop a Conditional Generative adversarial network (cGAN).

A generator tries to fool the discriminator and create realistic images while the discriminator figures out if the image is real or fake. A GAN network is very suitable when there is no clear pattern or we want to "create" new data samples. A generator creates new and realistic images from images, but in this project, we utilize Conditional GAN that takes additional data and conditions the fake data generation process to generate a particular type of fake data.

![gan_diagram](https://github.com/Mabinuv/GenAI_Proj---Using-Conditional-GAN/assets/117342411/4b70d77a-e89f-4532-9eba-a6031f1e539d)


The generator learns to generate plausible data. The generated instances become negative training examples for the discriminator.
The discriminator learns to distinguish the generator's fake data from real data. The discriminator penalizes the generator for producing implausible results.


Task
Given dataset contains sequence of image sets. There are multiple sets with distinct image sequences. Given the very first frame of a sequence, generate the last frame.

Implement a cGAN - Generator model that takes in the first frame as input and generates the respective last frame of that image sequence.


https://github.com/user-attachments/assets/fb4724b7-c7d7-4526-8722-ed0b08124ad5

