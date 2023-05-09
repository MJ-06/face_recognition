# face_recognition

Created a Basic Face recogniser using dlib library in python

Dlib is one og the biggest and fastest face detection library

Here we use dlib face_locations and face_encodings to find the location of faces present in the image and there respective featueres given in the form of an encoding.

We save a Pickle file containing a dictionary with encodings of each person's face, then every new image is scaned for face_encoding's which are matched with the saved encodings. The person with most matches is shown as the result.

P.S the more encodings the higher the accuracy.

P.S.S Adding Command Line arguments soon and Webcam Detection.
