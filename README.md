# FaceRead
A real-time facial expression detection system build with Python and OpenCV. FaceRead uses your webcam to detect faces and classify expressions into 7 emotions in real time.

#Emotions detected
1.Happy-Green
2.Sad-Blue
3.Angry-Red
4.Neutral-White
5.Fear-Yellow
6.surprise-Cyan
7.Disgust-Purple

#Features
1.Real-time webcam video processing
2.Face detection using Haar Cascade Classifier
3.Emotion recognition using FER
4.Displays detected emotion on the screen
5.Different colours for different emotions
6.Live emotion prediction

#Technologies used
1.Python
2.OpenCv
3.FER(Facial Emotion Recognition)
4.Haar Cascade Face Detection

#How it works
1.OpenCV captures live video from your webcam
2.Haar Cascade Classifier detects the face
3.The detected face is cropped and passed to the FER model
4.FER library analyzes the cropped face and predict emotions
5.The emotions with the heighest confidence score is selected
6.A coloured rectangle and emotion label are drawn around the face
