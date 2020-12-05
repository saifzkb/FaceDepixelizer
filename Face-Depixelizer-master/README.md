## NOTE
We have noticed a lot of concern that PULSE will be used to identify individuals whose faces have been blurred out. We want to emphasize that this is impossible - **PULSE makes imaginary faces of people who do not exist, which should not be confused for real people.** It will **not** help identify or reconstruct the original image.


If you are interested more about the topic, you can read this [IEEE Tech Talk about PULSE](https://spectrum.ieee.org/tech-talk/computing/software/making-blurry-faces-photorealistic-goes-only-so-far).

# Face-Depixelizer
Face Depixelizer based on "PULSE: Self-Supervised Photo Upsampling via Latent Space Exploration of Generative Models" repository. 

![example](https://github.com/tg-bomze/Face-Depixelizer/raw/master/transformation.gif)

Given a low-resolution input image, Face Depixelizer searches the outputs of a generative model (here, [StyleGAN](https://github.com/NVlabs/stylegan)) for high-resolution images that are perceptually realistic and downscale correctly.


