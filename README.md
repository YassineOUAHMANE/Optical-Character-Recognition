# 📝 OCR with Thresholding
## 📜 Project Overview
This project demonstrates the use of Optical Character Recognition (OCR) techniques to extract text from images. A key focus of the project is thresholding, which enhances image contrast and helps the OCR engine achieve more accurate results. By experimenting with different thresholding parameters, we aim to optimize text extraction.

## 📦 Prerequisites
Ensure you have the following installed before running the project:
Python 3.x
OpenCV (pip install opencv-python)
Tesseract-OCR (pip install pytesseract)
Matplotlib (for visualizing results, pip install matplotlib)
You will also need to install Tesseract on your machine. Instructions can be found here: Tesseract Installation

## 🛠️ Key Libraries Used
OpenCV: For image pre-processing (thresholding, binarization, etc.)
Pytesseract: The OCR engine used to extract text from images.
Matplotlib: For displaying images and results of thresholding.
## 🖼️ Image Pre-processing
Thresholding is essential in the OCR pipeline. By converting the image to a binary format, OCR accuracy can be significantly improved. In this project, several thresholding techniques have been experimented with to find the optimal one for each image type.

## Thresholding Methods Used:
Global Thresholding: Simplest form where a single threshold value is applied to the entire image.
Adaptive Thresholding: Applies a different threshold for different regions of the image.

## 🎯 Objective
The goal is to test various thresholding methods and parameters on different images to find the best settings for accurate text recognition. Fine-tuning these settings helps in improving the clarity of the text extracted by the OCR engine.

## 📊 Sample Results
The project comes with a  sample image. Use other images Run the script and check the extracted text for each. Compare the results when using different thresholding techniques to observe how they impact OCR accuracy.

## 📖 Further Reading
For more in-depth discussion on this project, check out my article on LinkedIn where I dive deeper into the technical aspects and provide additional insights:
[check out my linkedin profile here🎉](https://www.linkedin.com/posts/yassine-ouahmane-8a15b6238_optical-character-recognition-activity-7203762868456960000-odW8?utm_source=share&utm_medium=member_desktop)
