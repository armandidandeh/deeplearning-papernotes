Okay, we get a twitter paper in here. So these guys make some really photorealistic images. They use a traditional GAN architecture but instead of using a pixel wise loss they use a perceptual loss which looks at the activations at multiple levels in a pretrained network and compares them across base and generated images. The adversarial loss is nearly the same. The images look good.