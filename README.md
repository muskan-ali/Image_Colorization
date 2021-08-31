# Image_Colorization
Color is one of the primary elements in an image responsible for making it feel exciting, lively, mysterious or melancholic or even depressing, so color makes an image meaningful and informative.
For example by looking in the below image we can say that the soft colors make the whole image look peaceful, intimate and a bit mysterious at the same time but if this image was in black and white so Would we have the same impact of the photo ? Definitely not!
![image](https://user-images.githubusercontent.com/65805215/131584575-46cf5144-a057-4cbc-b342-112569b7d7dd.png)

There exist a large number of black and white historic images which can be converted into color images and we can achieve this by image colorization technique.
The ultimate objective of image colorization is to map a gray-scale image into a meaningful color image, so using deep learning we will try to achieve this.

Image Colorization process involves the following steps:
•	We will load the RGB images.
•	RGB images will be converted into Lab color space.( L stands for lightness like how light is the image so L channel image will look like a black and white image or grayscale image and on top of that L channel we add a and b channel, where a channel goes from green to red color and b channel goes from yellow to blue color, and this gives a colorized image.)
  
![image](https://user-images.githubusercontent.com/65805215/131584667-41b8f1ab-a958-4e42-bd15-1f35903ae5ec.png)


•	We will train a model which will learn how to colorize other images so basically we are trying to predict a and b channel and then we will add that on top our L channel.
•	Then our final Lab color space image will be converted into RGB image and that will be a colorized image.
![image](https://user-images.githubusercontent.com/65805215/131584741-47e8afa1-fb12-429d-936d-fc2a61b6c1da.png)
