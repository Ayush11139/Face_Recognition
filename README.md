# Installation
you can find complete procedure for installation in MAC/Ubuntu in
https://pyimagesearch.com/2017/03/27/how-to-install-dlib/


# Facial Landmarks used
Eyes
Eyebrows
Nose
Mouth
Jawline


# Face_Recognition
Detecting facial landmarks is therefore a two step process:
Step #1: Localize the face in the image.
Step #2: Detect the key facial structures on the face ROI.





Lines 34-39
dlib has pre-trained facial landmark detector.It can easily be found at http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2
--image : The path to the input image that we want to detect facial landmarks on.

