# BW2Color
The goal of the project is to make a model that transforms black and white images to RGB images. Basicaly, to colorize them.
My objectives, apart from learning and experimenting, was to use a model trained in some images with some specific asthetics, and use it in differet ones.

As the result's aren't too good in the beguining, I changed to the LAB color space. It has one black and white chanel, and two color chanels. That way the black and white imput image is reused, and only the color is predicted. That way, even if the colorization is not too good, the image is recognizable.

The results are rether bad. All decent models were heavly overfitted, as the amount of data was very small. There were some succeses in the testing data, but it was because they were very similar to some training images. 

In some runs it did get some basic generalizations. **It was able to colorize the blue sky and draw a spot of skin color in faces.**

## Examples

![image](https://user-images.githubusercontent.com/32079160/147974080-0b5e0c12-3839-4c79-8163-e1edc8063fc1.png)

<img src="https://user-images.githubusercontent.com/32079160/147974519-be6c08eb-bf01-44a4-b91c-37ec439a0306.png" width="255" height="255"> <img src="https://user-images.githubusercontent.com/32079160/147974792-4933b7d4-5bb5-4e45-90a9-b4732f2014f9.png" width="255" height="255"><img src="https://user-images.githubusercontent.com/32079160/147974952-537c52d1-4bf4-47c7-b757-f86ad5440a44.png"  width="255" height="255">

