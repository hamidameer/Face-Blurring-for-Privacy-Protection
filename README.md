# Face Blurring for Privacy Protection

## Project Overview

This project presents an automated face-blurring system designed to protect privacy in images by detecting and anonymizing human faces. With increasing concerns around digital privacy, the system helps prevent identity exposure in shared media such as social platforms, news content, and professional use.

## Objectives
Detect human faces in images automatically
Improve image quality to enhance detection accuracy
Extract and isolate face regions
Apply blurring to protect identity
 
## Methodology

The system follows a simple image processing pipeline:

### Preprocessing
-Convert image to grayscale
-Apply histogram equalization for contrast enhancement
-Reduce noise using Gaussian blur
### Face Detection
-Use Haar Cascade classifier to detect faces
### Segmentation
-Extract bounding box coordinates of detected faces
### Face Blurring
-Apply Gaussian blur to detected face regions only
-Merge blurred regions back into the original image

## Techniques Used
-Image processing (OpenCV)
-Haar Cascade face detection
-Gaussian Blur filtering
-Basic segmentation
