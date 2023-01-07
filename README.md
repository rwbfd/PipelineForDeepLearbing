# A Pipeline for Deep Learning
## Goals

The goal of composing this library is to combine the famous StyleGAN-XL code with 
variational diffusion models into a unified template. In this regard there are several 
goals that we aim to provide:

1. A template where one can plug in the complex training processes, including but not limited to generative training, sampling, and data augmentation.
2. A template where one can write custom cuda kernels to speed up processes.
3. A template that supports both GPU and TPU.
4. A template that allows for multiple level of optimization.
5. A template that allows for profiling. 
6. A template to support quantification. 

## To-Do
1. AMP
2. 