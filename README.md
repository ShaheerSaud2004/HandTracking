# HandTracking Module

This project involves developing a hand detection program in Python, which uses OpenCV, MediaPipe, and other libraries to detect hands in a live feed from a webcam. It identifies individual hand landmarks and implements several functionalities including tracking and distance measurement.

Code Explanation:

Class Definition (handDetector): The primary class that houses the detection and tracking mechanisms.

Init method (__init__): Initial parameters such as detection confidence and tracking confidence are set.

Find Hands (findHands): The method uses OpenCV to process images from webcam feed, detects hands in them and draws landmarks if required.

Find Position (findPosition): Determines the position of landmarks on the detected hands and creates a bounding box around the hand.

Finger Up (fingerUp): The method used to check whether fingers are open (up) or closed (down) based on the position of landmarks.

Distance (Distance): This function calculates the distance between two fingers, uses a simple line equation.

Main Function (main): Initializes and controls the hand detection process, outputs the webcam feed with the processed frames.
