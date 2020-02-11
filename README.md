# Intruder Detection -version 2.0
Here we use face_recognition python module. This module runs upon dlib a c++ based library.
It consists of 4 steps.
## Step-1 : Encode the picture using the HOG algorithm to create a simplified version of the image.
# Step-2 : Finding the main landmarks in the face like nose, mouth and ears.
# Step-3 : Encoding Faces. Here we use a pre-trained Convolution Neural Network developed by OpenFace.
# Step-4 : Finding the person’s name from the encoding.Compare which person has the closest measurements to our face’s measurements.

Referenced from : https://github.com/ageitgey/face_recognition/blob/master/examples/facerec_from_webcam.py
