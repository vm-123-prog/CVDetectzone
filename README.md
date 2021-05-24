# CVDetectzone
A library for face detection and recognition within single line of code
Modules:
=>FaceDetection
  >difffaces(pathtoimg1,pathtoimg2)
  >trainwebcam(PathToDirectoryWhereKnownFacesImages, cameraindex, window name)
=>HandFingersDetection
  >detectfingers(window name,cameraindex)
  >detecthand(window name,cameraindex)

===>difffaces is a function to see whether two faces in images are same or not
===>trainwebcam is a function in which you have to provide path to directory which contains images of known faces and give name to window and set index of camera, after giving this much details it will automatically start camera and start recognising faces from the images provided in knwon faces directory.
===>detectfingers is a function which will detect how many fingers are up and how many fingers are down and will print the result
===>detecthand is function for detecting hand.
