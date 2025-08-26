# Diffusion-Models
Diffusion Models

<img width="550" height="170" alt="image" src="https://github.com/user-attachments/assets/26222222-0ce3-462d-8f3a-804561816915" />

In Variational Auto Encoders, we can sample from the latent space to generate new data points.

<img width="550" height="340" alt="image" src="https://github.com/user-attachments/assets/12cf5929-555b-427d-9046-7201fe8754bf" />

GANs are hard to train due to issues like vanishing gradients or mode collapse.

<img width="574" height="313" alt="image" src="https://github.com/user-attachments/assets/3bd0c7a7-0ff7-4539-9742-e7fd8847e93e" />

First Noise is added to the image to destroy the image. Then randomly denoising is performed on the image. Typically 1000 step are chosen.

<img width="500" height="320" alt="image" src="https://github.com/user-attachments/assets/759c35c2-bbb8-4ca0-af9b-5777021e6a6d" />

Three things are required for Diffusion models, 
1. Noise Scheduler, scheduler to sequentially adds noise.
2. Neural Network, model to predict the noise in an image.
3. Timestamp Encoder, mechanism to encode the current timestep.


<img width="530" height="254" alt="image" src="https://github.com/user-attachments/assets/1e551c8f-775c-4af7-8bce-ec2dd9277218" />


<img width="871" height="343" alt="image" src="https://github.com/user-attachments/assets/1b76a7b3-04c3-4466-815f-2c4d59c86bad" />

The loss function

