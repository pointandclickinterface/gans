# Generative Adversarial Networks #

Generative Adversarial Networks or GANs in a nutshell are a type of deep learning model in which two neural networks (the Generator and the Descrminator) compete against eachother in a sort of zero sum game. The Generator network generates content from randomness and improves upon it until it can reasonably convice the Descrimiator that it matches the training input.

This is my repo where I keep the GANs I have made.

I make them as ipynb files to allow for easy reading of them but a future goal is to make regular python modules out of them to make them more usable/object oriented in the future.

## DC GAN 1 ##

This is my first DC gan. It uses pytorch and procedurally generates images that are 128 x 128 pixels. Images need to all be the same size to use this and it works better if they are square. I recommend my [image cropper](https://github.com/pointandclickinterface/image-processing/tree/main/Google%20Drive%20Image%20Cropper) for this job.
