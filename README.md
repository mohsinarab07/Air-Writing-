# Air-Writing Recognization 

- Air Writing Recognition system that detects and classifies handwritten alphabets and digits using hand gestures, powered by MediaPipe, OpenCV, TensorFlow, Flask, and PyGame.

- This project allows users to write in the air using finger movements in front of a webcam. The system captures the motion, draws it virtually, and then recognizes the drawn character (either alphabet or digit) using trained deep learning models
# Features:
-Real-time hand tracking with MediaPipe
-virtual paint interface using OpenCV and PyGame
-Alphabet and digit recognition using TensorFlow Keras model
-Dynamic mode switching: alphabets, digits, erasing, off
-Gesture-controlled tool selection (draw, line, rectangle, circle, eraser)
-Web integration with Flask (for modular deployment)

#Tech Stack
Python =	Core language
OpenCV =	Video stream processing, drawing
MediaPipe	= Hand landmark detection
PyGame	= Virtual canvas for drawing
TensorFlow/Keras	= Model prediction for digits/alphabets
Flask	Web routing =(modular use of blueprint)
NumPy =	Array manipulation
Keyboard	= Key-based gesture mode switching

#Working : 

*Hand Detection
Using MediaPipe, we detect 21 hand landmarks to determine finger positions and motions.

*Drawing Logic
Depending on which fingers are raised:
Index only → Drawing
Index + Middle → Tool switching

*Model Prediction
When the gesture drawing is complete:
The virtual canvas area is cropped and resized to 28x28
Preprocessed and fed to a CNN model
Returns the predicted alphabet or digit

Connect with Me
💼 [Mohsin Arab] | [https://www.linkedin.com/in/mohsin-arab-2748bb236?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app]
💻 GitHub: [mohsinarab07]
📧 Email: [mohsinarab063@gmail.com]



