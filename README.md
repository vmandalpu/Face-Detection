# Facial Recognition Using Neural Networks

In this notebook, we will not go thru the hassle of training or building neural network model,  We have access to a trained model through dlib that we can use. It does exactly what we need it to do — outputs a bunch of numbers (face encodings) when we pass in the image of someone’s face; comparing face encodings of faces from different images will tell us if someone’s face matches with anyone we have images of. 

Here are the steps we will be taking:

Detect/identify faces in an image (using a face detection model) — for simplicity, this notebook will only use images with one    face/person in it, not more/less

Predict face poses/landmarks (for the faces identified in step 1)

Using data from step 2 and the actual image, calculate face encodings (numbers that describe the face)

Compare the face encodings of known faces with those from test images to tell who is in the picture
