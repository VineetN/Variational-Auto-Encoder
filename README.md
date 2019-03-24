# Variational-Auto-Encoder
This is to design a Variational Auto-Encoder using the MNIST dataset to predict numerical characters.
I am first training an encoder to reduce the dimensionality of the latent space, then a decoder to produce another image,
as close to the original as possible from the encoder.
After this, I cut off the decoder from the model and add a dense layer on top of my encoder which I train further and see if there
is a marked difference in accuracy.
I compare this apporach to the standard Conv layer model which is genrally used for this prediction task.
