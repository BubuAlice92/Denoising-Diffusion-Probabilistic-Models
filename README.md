# Denoising Diffusion Probabilistic Models
Implementation of Denoising Diffusion Probabilistic Model in Pytorch.

Source: https://github.com/lucidrains/denoising-diffusion-pytorch/

Paper: J. Ho. and al., Denoising Diffusion Probabilistic Models, 2020

In simple terms, noise is added to an image step by step. 
Then a model is trained to predict that noise at each step.
Finally, the the model is used to generate images.
