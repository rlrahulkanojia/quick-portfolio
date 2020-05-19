## Super Resolution Generative Adversial Network 

**Project description:** 

The input is pair of the images of the person and the cloth. The output is the fitted image of the cloth on the person. 


### 1. Architecture Details

The architecture of SRGAN consists of a Generator and a Discriminator. The Generator uses a Gausian noise to fit to the data and generate the images. The discriminator is trained directly on real and generated images and is responsible for classifying images as real or fake (generated). The generator is not trained directly and instead is trained via the discriminator model

<img src="images/SRGAN/architecture.png?raw=true"/>

### 2. Link to source Code

The Code has been implemented in Google Colaboratory and is ready to use and free to extend to other aplications.
The code can be found <a href='https://colab.research.google.com/drive/1CNhuEKtLzUhlHhw5ag-6FLjZj8Pe_I8o#scrollTo=K6Ccj64AtlK8'>**HERE**</a>

