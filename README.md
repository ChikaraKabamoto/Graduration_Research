# Virtual Tryon System
Demonstrates a virtual fitting system with deep learning. In previous research, there was the problem that it was difficult to express clothing logos and patterns using deep learning alone. In addition, only existing clothing designs were available, and there was not a wide variety of clothing designs. The code, dataset, and trained model are shown below. You can get an image of the following fitting diagram from the trained model.

## Code
The code below is coded in "Pytorch" and can be executed in "Google Colaboratory".
### 1.VirtualTryon.ipynb
#### Abstract
It is a virtual fitting code of existing clothes by autoencoder. Only the tops are tried on, and the Patch GAN structure is used for the Discriminator so that the logo and pattern can be expressed.
#### Data
The datasets and trained models needed to run are here.
#### Method    
Place the zip file downloaded above in "MyDrive" and unzip it.
It will take some time to decompress.
~~~!unzip VirtualTryon_data.zip~~~
<br>
<br>
<br>


### 2.DiversityDesign.ipynb
#### Abstract
It is a fitting code of diversity design by VAEGAN which combined VAE and GAN. In order to solve the problem of the conventional virtual fitting system, "lack of diversity", the colors of tops, pants, and skirts can be changed to various colors by sample noise from the latent space.
#### Data
The datasets and trained models needed to run are here.
We will also publish another dataset with colored clothing.
#### Method
Place the zip file downloaded above in "MyDrive" and unzip it.
It will take some time to decompress.
<br>
<br>
<br>


### 3.VirtualTryonSystem.ipynb
#### Abstract
It is a virtual fitting system modeled on "Diversity Design.ipynb". You can change the color of tops, pants, and skirts in portrait images taken with the camera. Find the coordination that suits you!
#### Data
The trained models needed to run is here.
#### Method
Place the zip file downloaded above in "MyDrive" and unzip it.
It will take some time to decompress.
<br>
<br>
<br>
