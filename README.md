# AirDrawCanvas
Ever wanted to draw your imagination by just waving your finger in the air.
In this post, we will learn to build an Air Canvas which can draw anything on it by just capturing the motion of a colored marker with a camera.
Here a colored object at the tip of the finger is used as the marker.
We will be using the computer vision techniques of OpenCV to build this project.
The preferred language is Python due to its exhaustive libraries and easy to use syntax but understanding the basics it can be implemented in any OpenCV supported language.
Here Color Detection and tracking are used in order to achieve the objective.
The color marker is detected and a mask is produced. It includes the further steps of morphological operations on the mask produced which are Erosion and Dilation.
Erosion reduces the impurities present in the mask and dilation further restores the eroded main mask.


