# Virtual Tryon System
Demonstrates a virtual fitting system with deep learning. In previous research, there was the problem that it was difficult to express clothing logos and patterns using deep learning alone. In addition, only existing clothing designs were available, and there was not a wide variety of clothing designs. The code, dataset, and trained model are shown below. You can get an image of the following fitting diagram from the trained model.

<img src="https://user-images.githubusercontent.com/59815704/107754840-634c4780-6d65-11eb-9ab4-50d828f286c3.png" width="500px">

## Code
The code below is coded in "Pytorch" and can be executed in "Google Colaboratory".
### 1.VirtualTryon.ipynb
#### Abstract
It is a virtual fitting code of existing clothes by autoencoder. Only the tops are tried on, and the Patch GAN structure is used for the Discriminator so that the logo and pattern can be expressed.
#### Data
The datasets and trained models needed to run are [here](https://drive.google.com/file/d/1TWCL0AjNMzYCELbIfceINl9fEJIZe84A/view?usp=sharing).
#### Method    
Place the zip file downloaded above in "MyDrive" and unzip it.
It will take some time to decompress.

```!unzip VirtualTryon_data.zip```
<br>
<br>
<br>


### 2.DiversityDesign.ipynb
#### Abstract
It is a fitting code of diversity design by VAEGAN which combined VAE and GAN. In order to solve the problem of the conventional virtual fitting system, "lack of diversity", the colors of tops, pants, and skirts can be changed to various colors by sample noise from the latent space.
#### Data
The datasets and trained models needed to run are [here](https://drive.google.com/file/d/1O2mOSr2WopSaU_6WI774AMcEcP6eryG1/view?usp=sharing).

We will also publish another [dataset](https://drive.google.com/file/d/1usF2XG_tZAPccnIU44XDE03Sz_nByEkl/view?usp=sharing) with colored clothing.
#### Method
Place the zip file downloaded above in "MyDrive" and unzip it.
It will take some time to decompress.

```!unzip DiversityDesign_data.zip```

```!unzip color_data.zip```
<br>
<br>
<br>


### 3.VirtualTryonSystem.ipynb
#### Abstract
It is a virtual fitting system modeled on "Diversity Design.ipynb". You can change the color of tops, pants, and skirts in portrait images taken with the camera. Find the coordination that suits you!
#### Data
The trained models needed to run is [here](https://drive.google.com/file/d/1O2mOSr2WopSaU_6WI774AMcEcP6eryG1/view?usp=sharing).

Click [here](https://drive.google.com/file/d/11MpsILUA8BG1coG_WwXFinQThJH6rj6D/view?usp=sharing) for the Seg model required for the system
#### Method
Place the zip file downloaded above in "MyDrive" and unzip it.
It will take some time to decompress.

```!unzip DiversityDesign_data.zip```

```!unzip segmentation.zip```
<br>
<br>
<br>
