# Large-Scale-Image-Classification-and-Similarity-Detection-with-Flask
This project is a Flask-based web application that classifies and identifies similar images from a dataset of 50,000 images. It supports efficient image classification into 20 categories and matches user-uploaded images with pre-processed data stored in pickle files.

Introduction
This project is aimed at handling large-scale image classification and similarity detection by processing and categorizing 50,000 images into 20 distinct categories. It utilizes Flask for the web interface, OpenCV for image processing, and pickle for data storage and retrieval.

Features
Large-Scale Classification: Efficiently classifies 50,000 images into 20 categories.
Pre-Processed Data Storage: Uses pickle files to store pre-processed image data for quick access.
User-Friendly Upload Interface: Allows users to upload images via a web interface.
Similarity Matching: Matches uploaded images with the most similar category.
Visual Verification: Displays the top 10 similar images from the identified category to verify classification accuracy.

Process and classify your dataset of 50,000 images into 20 categories.
Store pre-processed data and category information in pickle files.
Create Pickle Files:

Save the classified images and their data in pickle files for each category.
Flask Application
Set Up Flask Application:
Integrate the image classification and similarity detection logic into the Flask app.
Ensure that the pre-processed data stored in pickle files is loaded and accessible for comparison during user interactions.
