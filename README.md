# CNN_Autoencoder
CNN to get denoised data from noisy data.

1. Generate a CNN model in which the input is a noisy number and the output is a denoised number. 
2. MNIST dataset. 
3. Use Gaussian distribution to add noise to the input. 
4. Train the model using Google Colab (TPU) for 100 epochs.
5. Plot the training & validation loss. 
6. Build a classifier based on the trained Autoencoder. 

## Input:
![Input Samples](https://github.com/Batserine/CNN_Autoencoder/blob/master/Screenshot%20from%202020-02-22%2015-51-50.png)
## Model Architecture:
![Model Architecture](https://github.com/Batserine/CNN_Autoencoder/blob/master/Screenshot%20from%202020-02-22%2015-52-04.png)
## Loss Curve:
![Loss Curve](https://github.com/Batserine/CNN_Autoencoder/blob/master/Screenshot%20from%202020-02-22%2015-52-23.png)
## Output:
![Output](https://github.com/Batserine/CNN_Autoencoder/blob/master/Screenshot%20from%202020-02-22%2015-52-33.png)

## References:
[MNIST Dataset](http://yann.lecun.com/exdb/mnist/)<br/>
[Building Autoencoders in Keras](https://blog.keras.io/building-autoencoders-in-keras.html)<br/>
[Denoising Autoencoder](http://dkopczyk.quantee.co.uk/dae-part1/)<br/>
