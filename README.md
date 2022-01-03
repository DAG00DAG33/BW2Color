# BW2Color
The goal of the project is to make a model that transforms black and white images to RGB images. Basicaly, to colorize them.
My objectives, apart from learning and experimenting, was to use a model trained in some images with some specific asthetics, and use it in differet ones.

As the result's aren't too good in the beguining, I changed to the LAB color space. It has one black and white chanel, and two color chanels. That way the black and white imput image is reused, and only the color is predicted. That way, even if the colorization is not too good, the image is recognizable.

The results are rether bad. All decent models were heavly overfitted, as the amount of data was very small. There were some succeses in the testing data, but it was because they were very similar to some training images. 

In some runs it did get some basic generalizations. **It was able to colorize the blue sky and draw a spot of skin color in faces.**
