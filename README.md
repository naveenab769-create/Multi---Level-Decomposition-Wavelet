Project Title :

Multi-Level Wavelet Decomposition (Level 1–3) for Image Analysis using DWT

 Project Description :

This project implements Discrete Wavelet Transform (DWT) to perform multi-resolution analysis (MRA) on grayscale images.
The image is decomposed into Approximation (LL) and Detail (LH, HL, HH) sub-bands up to Level-3, enabling effective texture and frequency-based feature extraction.

Wavelet coefficients are further analyzed using statistical features like Energy, Entropy, Mean, and Standard Deviation, which are widely used in medical imaging, texture classification, and pattern recognition.

 Objectives of the Project :

No vague objectives. These are interview-ready:

To perform multi-level (Level 1–3) wavelet decomposition on grayscale images
To visualize horizontal, vertical, and diagonal details at each decomposition level
To extract statistical features from wavelet sub-bands
To understand frequency-domain representation of images
To prepare a feature vector suitable for machine learning / image classification tasks

 Why Wavelet Decomposition?

Traditional image analysis methods like Fourier Transform fail to provide spatial + frequency localization.
Wavelet Transform solves this problem.

✔ Advantages of Wavelets:

Provides multi-resolution analysis
Captures both spatial and frequency information
Works well for non-stationary signals (images are non-stationary)
Efficient for edge, texture, and noise analysis

That’s why wavelets are heavily used in:

MRI / CT image analysis
Texture classification
Image compression (JPEG2000)
Feature extraction for ML models

 Why Discrete Wavelet Transform (DWT)?
 
DWT is computationally efficient
Suitable for digital images
Produces compact and meaningful coefficients
Easy to extract statistical features from sub-bands

In this project, Daubechies (db2) wavelet is used because:
It provides better smoothness than Haar
Preserves important image details
Commonly used in real-world image processing tasks

 Methodology / Technique Used :
 
Load grayscale image (or generate synthetic image)
Apply 2D Discrete Wavelet Transform

Decompose image into:
LL → Approximation
LH → Horizontal details
HL → Vertical details
HH → Diagonal details
Perform decomposition up to Level 3
Visualize wavelet sub-bands

Extract statistical features:
Energy
Entropy
Mean
Standard Deviation
Store features as a structured feature vector

📊 Output of the Program :

The program was tested using real-world images such as a rose and a cat. For each image, multi-level (Level 1–3) wavelet decomposition is performed, producing approximation and detail sub-bands. The output includes clear visualization of texture and edge details along with extracted statistical features forming a final feature vector.

These features can be directly used for:
Image classification
Disease detection (MRI / CT)
Texture analysis

Tools & Libraries :
Python
OpenCV
PyWavelets
NumPy
Matplotlib
Pandas

 Applications :
Medical image analysis
Image denoising
Texture classification
Pattern recognition
Pre-processing for AI / ML models

This project demonstrates how wavelet-based multi-resolution analysis can effectively represent image information across different frequency bands, making it suitable for advanced image processing and machine learning applications.
