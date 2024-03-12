## abandoned place
The main idea finding the flag hidden inside an image which its dimension is manipulated.


#### Problem Statement:
<p align="center">
<img src="resources/images/abandoned place.png">
<br>


#### Step-1:
Open the image inside CyberChef and convert it to hex.

#### demonistration:
<p align="center">
<img src="resources/images/tohex.png">
<br>

#### Step-2:
Replace input with output in CyberChef.


#### Step-3:
Hold ctrl+F in the output field and search for ff c0. Note the following values starting at ff c0:

`ff c0 00 11 08 03 84 07 e0`

#### the relevant bytes and what they mean in the image below:
<p align="center">
<img src="resources/images/out.png">
<br>

#### demonistration:
<p align="center">
<img src="resources/images/WebPage.png">
<br>

#### Step-4
I changed the bytes to :

`ff c0 00 11 08 08 84 07 e0`

#### Step-5
add "from hex" and "render image" in CyberChef operation panel and save the image

#### demonistration:
<p align="center">
<img src="resources/images/WebPage.png">
<br>

#### Output image will be:
<p align="center">
<img src="resources/images/WebPage.png">
<br>


#### The Flag is obtained:
`CTFlearn{urban_exploration}`
