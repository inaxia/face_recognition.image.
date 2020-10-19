# Face Recognition (image)

This project is based on Artificial Intelligence & Machine Learning
Using some libraries like: os, opencv & face_recognition

## Project Summary

1. initialCode.py (first attempt to detect face in an image)

   In this, we have used 2 libraries: opencv & face_recognition.

   i. face_recognition:

      we used `load_image_file` for loading an image from `assets` folder,

      we have also used `face_locations` to find the face in that image,

      we used `face_encodings` to get 128 measurements of that face,

      and finally used `compare_faces` to compare two faces.
