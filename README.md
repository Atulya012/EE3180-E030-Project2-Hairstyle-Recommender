# **Hairstyle Recommender Model**

## Overview

This project is a hairstyle recommendation system which identifies the user's face shape and showcases hairstyles best suited to them in real time.

## Features

  - Facial detection and classifcation via OpenCV's Haar Casacde classifer, face_recognition library based on dlib's shape_predictor_68_face_landmarks, and a Multilayer Perceptron Model
  - Real time video analysis and haircut overlay display
  - Face Shape classified via placement of landmark points across the face, angles between the chin and other points on the face, and width and ratio of the jaw as compared to the rest of the face
