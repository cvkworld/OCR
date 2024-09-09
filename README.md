# OCR: Scene Text Detection and Recognition
Scene text detection and recognition:
  
This project implements text detection in the wild using the EAST (Efficient and Accurate Scene Text) detection technique and Tesseract OCR for text recognition.

# Overview
The primary goal is to detect and recognize text from images, including scenes or natural environments where text may appear. The pipeline first detects text regions using the EAST model, and then extracts the text using Tesseract OCR.

# Requirements
# 1. Install Tesseract OCR

To recognize text from an image, you must install Tesseract OCR. For best results, use Tesseract version 4 or higher.

* Download and install the Tesseract binaries for your operating system from the Tesseract GitHub Wiki.
# 2. Download EAST Text Detection Model
You will also need the pre-trained EAST model, which is required for text detection:

* Download frozen_east_text_detection.pb from a trusted source.

# 3. Additional Dependencies
* Ensure that your environment has necessary Python libraries such as opencv-python, numpy, and pytesseract. These can be installed using pip:

## Installation

Install the required dependencies:

<pre>  pip install opencv-python numpy pytesseract  </pre>




#  Usage
After setting up the environment, you can use the project to detect and recognize text in images.
# Run your script

<pre>  python ocr_text_detection.py --image path_to_image.jpg  </pre> 
 # Some Testing Images:
 Here are some example images tested with this setup:
 
 ![test Images](licence_plate1_test/test09.jpg)
 
 
 ![test Images2](https://github.com/cvkworld/OCR/blob/master/licence_plate1_test/test04.jpg)
 
# References
* [Tesseract OCR Documentation](https://tesseract-ocr.github.io/)
* [EAST: An Efficient and Accurate Scene Text Detector](https://arxiv.org/abs/1704.03155)
