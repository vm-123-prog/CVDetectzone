# CvDetectZone
A library for face detection and recognition within single line of code

[![Downloads](https://pepy.tech/badge/cvdetectzone)](https://pepy.tech/project/cvdetectzone) [![Downloads](https://pepy.tech/badge/cvdetectzone/month)](https://pepy.tech/project/cvdetectzone) [![Downloads](https://pepy.tech/badge/cvdetectzone/week)](https://pepy.tech/project/cvdetectzone) 

**Face Detection**

 - difffaces(pathtoimg1,pathtoimg2)
 - trainwebcam(PathToDirectoryWhereKnownFacesImages, cameraindex, window name

**Hands & Finger Detection**

 - detectfingers(window name,cameraindex)
 - detecthand(window name,cameraindex) 

 

 1. **difffaces()** is a function to see whether two faces in images are same or not
 2. **trainwebcam()** is a function in which you have to provide path to directory which contains images of known faces and give name to window and set index of camera, after giving this much details it will automatically start camera and start recognising faces from the images provided in knwon faces directory.
 3. **detectfingers()** is a function which will detect how many fingers are up and how many fingers are down and will print the result
 4. **detecthand()** is function for detecting hand.
