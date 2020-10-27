# Real-time Facial Expression Recognition using Keras, OpenCV and Flask

This program trains a convolutional neural network (CNN) in Keras to recognize facial expressions (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). Program is trained on the data FER 2013. OpenCV is used to detect faces in images and draw bounding boxes around them then the trained model will classify it and visualize it on the web interface using Flask in real-time.

    python3 main.py
    
If you want to use your own video rather than the webcam please change the 11th line in the camera.py

    self.video = cv2.VideoCapture(0)
to

    self.video = cv2.VideoCapture("/your_video")
    
[More details about the project](https://www.coursera.org/projects/facial-expression-recognition-keras)

