## Super Resolution Generative Adversial Network 

**Project description:** 

Super Resolution Generative Adversial Network takes low resolution images as input and generates the same image with higher resolution. This project uses public figure dataset. 


### 1. Architecture Details

The architecture of SRGAN consists of a Generator and a Discriminator. The Generator uses a Gausian noise to fit to the data and generate the images. The discriminator is trained directly on real and generated images and is responsible for classifying images as real or fake (generated). The generator is not trained directly and instead is trained via the discriminator model

<img src="images/SRGAN/architecture.png?raw=true"/>
<!-- 
```javascript
if (isAwesome){
  return true
}
``` -->

### 2. Link to source Code

The Code has been implemented in Google Colaboratory and is ready to use and free to extend to other aplications.
The code can be found <a href='https://colab.research.google.com/drive/1CNhuEKtLzUhlHhw5ag-6FLjZj8Pe_I8o#scrollTo=K6Ccj64AtlK8'>here</a>

<img src="images/efficient/compare.png?raw=true"/>

<br><br>

<img src="images/efficient/params.png?raw=true"/>
<!-- ```javascript
if (isAwesome){
  return true
}
``` -->

