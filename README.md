# MeXEE402_Finals_Catambay_4101

# INTRODUCTION

In computer vision, face detection and privacy protection are crucial applications. One common approach to protecting personal information is to blur or hide certain facial features in images, especially the face and eyes. Image blurring techniques can help obscure sensitive data, while maintaining the structure of the surrounding scene. Detecting specific areas for blurring, like the eyes and face, is essential for preserving privacy and anonymity in visual content. This project focuses on utilizing image blurring techniques to detect and hide the eyes in images to ensure privacy.

# ABSTRACT
The objective of this project is to explore and implement image blurring techniques for the purpose of detecting and concealing faces and eyes in digital images. By leveraging computer vision algorithms, we aim to automatically identify facial features and apply a blur effect to them. The project will involve using pre-trained machine learning models for face detection and eye detection, followed by the application of image processing techniques to blur these areas. The expected result is a system that effectively protects privacy while preserving the rest of the image in its original form.

# PROJECT METHODS

Image Acquisition:

• Obtain a collection of images containing human faces, including different angles and lighting conditions.

Preprocessing:

• Convert images to blue image to simplify processing.
• Normalize image size for consistency.

Face Detection:

• Use a pre-trained model (e.g., OpenCV's Haar cascades) to identify faces in the image.
• Extract the bounding box coordinates of detected faces.

Eye Detection:

• Within the detected face region, use another model or algorithm to detect eyes.
• Store the coordinates of the eyes.

Blurring Techniques:

• Apply Gaussian blur to the face and eye regions.
• Adjust the intensity of the blur to balance privacy and image clarity.

Image Reconstruction:

• Combine the blurred face and eyes with the unchanged portions of the image.
• Output the modified image.

# Evaluation:

• Assess the quality of the blurring, ensuring that the face and eyes are sufficiently obscured while the rest of the image remains intact.

# CONCLUSION

The project successfully demonstrated the effectiveness of image blurring techniques to hide the identity of individuals by detecting and blurring faces and eyes. The challenges included ensuring accurate face and eye detection under varying conditions and fine-tuning the blurring process to avoid excessive distortion of the image. The results indicate that while face and eye blurring is effective for privacy protection, further optimization is needed to improve the accuracy of detection in complex environments. This approach provides a solid foundation for implementing privacy protection in visual data. 

# ADDITIONAL MATERIALS
1. Code:

Python code using OpenCV for face and eye detection.
Gaussian blur implementation.

2. Images:

Original and processed images demonstrating the blurring technique.

3. Results:

Evaluation metrics showing the success of face and eye blurring.

