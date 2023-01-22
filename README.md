# Signed-Unsigned-DL
A real-time dataset was collected, that is, a live stream video was converted to frames 
and each frame was of the category of either signing or not signing. 
The model was built using an architecture similar to VGG-16 architecture and was used to train the pre-processed frames.
Using StreamLit, a live streaming video was captured and absdiff frames were parallelly generated with the classification 
as signing or not signing. The final model was deployed on the Heroku Platform for public access.


VGG-16 ARCHITECTURE:

![image](https://user-images.githubusercontent.com/95125599/213904594-d8f10b33-4bc3-4065-9f3f-dd9f32f81bdf.png)




