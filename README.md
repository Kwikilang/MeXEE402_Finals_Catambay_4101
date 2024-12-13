# MeXEE402_Finals_Catambay_4101

# PROBLEM STATEMENT

As the use of facial recognition technology and image processing grows, ensuring privacy in digital images has become a significant concern. One of the key challenges in protecting individuals' identities is to effectively obscure sensitive facial features, such as the face and eyes, without compromising the quality of the rest of the image. The problem lies in applying image blurring techniques that can successfully detect and blur these facial features (face and eyes) while maintaining the integrity of the surrounding elements in the image. This project aims to develop an efficient system that detects faces and eyes in images and applies appropriate blurring techniques to anonymize these features, thus protecting privacy while ensuring the surrounding context remains intact.

# INTRODUCTION

In computer vision, privacy protection is a significant concern, especially when dealing with sensitive data, such as faces and eyes. One effective way to protect privacy is by using image blurring techniques to obscure facial features, thereby hiding the identity of individuals in images. This approach is essential in various applications, including surveillance, social media, and security systems, where it is necessary to anonymize or blur out identifiable features to prevent unauthorized identification.

# ABSTRACT
The objective of this project is to explore and implement image blurring techniques for the purpose of detecting and concealing faces and eyes in digital images. By leveraging computer vision algorithms, we aim to automatically identify facial features and apply a blur effect to them. The project will involve using pre-trained machine learning models for face detection and eye detection, followed by the application of image processing techniques to blur these areas. The expected result is a system that effectively protects privacy while preserving the rest of the image in its original form.

# PROJECT METHODS

Preprocess: 

• Convert images to blue image to simplify processing.
• Normalize image size for consistency.

Step 1: Image Input
• Load the input image that requires face and eye blurring.

Step 2: Face Detection
• Use a face detection algorithm (such as Haar Cascade) to identify the position of the face(s) in the image.

Step 3: Eye Detection
• Apply a similar face detection model to locate and segment the eyes within the detected face region.

Step 4: Apply Blurring Techniques
Select the blurring method(s) to be used:

•Median & Gaussian Blur: Apply a Gaussian filter to blur the entire face and eye regions.

Step 5: Anonymization
•Use blurring techniques to obscure facial features and the eye area to ensure privacy.

Step 6: Image Output
•Save or display the final output image with the blurred facial regions, ensuring that the rest of the image remains unaffected.

# Evaluation:

• Assess the quality of the blurring, ensuring that the face and eyes are sufficiently obscured while the rest of the image remains intact.

# CONCLUSION

The project successfully demonstrated the effectiveness of image blurring techniques to hide the identity of individuals by detecting and blurring faces and eyes. The challenges included ensuring accurate face and eye detection under varying conditions and fine-tuning the blurring process to avoid excessive distortion of the image. The results indicate that while face and eye blurring is effective for privacy protection, further optimization is needed to improve the accuracy of detection in complex environments. This approach provides a solid foundation for implementing privacy protection in visual data. 

# ADDITIONAL MATERIALS
1. Code:

•Python code using OpenCV for face and eye detection.
•Haar Cascade model for classifying face and eyes detection.
•Gaussian and Median blur implementation.

2. Images:

•Original and processed images demonstrating the blurring technique.

3. Results:

•The code will apply Gaussian blur to the face and eye regions of the image.
•It will output an image where faces and eyes are anonymized, helping to maintain privacy.

