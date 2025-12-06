# Computer Vision Lab Work

This repository contains 12 practical programs implementing fundamental computer vision techniques, from basic image processing to advanced filtering and edge detection.

## Programs Overview

### Program 1: Convolution and Correlation Operations
- Implemented image filtering using convolution and correlation
- Defined custom kernel for edge detection
- Applied filter2D operations using OpenCV
- Demonstrated the difference between convolution (kernel flipping) and correlation
- Tested on sample image to visualize effects

**Screenshot**

<img width="449" height="258" alt="image" src="https://github.com/user-attachments/assets/c7c33db5-9606-44a6-a660-a01f4dcc81d7" />
<img width="449" height="511" alt="image" src="https://github.com/user-attachments/assets/a9c24e29-5764-4958-96ea-61b6df4aa81e" />


---

### Program 2: Geometric Transformations
- Implemented affine transformations: identity, translation, scaling, rotation, reflection, shear
- Combined multiple transformations into single operation
- Used scikit-image for affine transformations
- Created comprehensive visualization grid showing all transformations
- Applied transformations to Ronaldo image for comparison

**Screenshot**

<img width="471" height="310" alt="image" src="https://github.com/user-attachments/assets/947a68e5-0d9a-43a1-b8b2-91e2d75ce550" />
<img width="702" height="506" alt="image" src="https://github.com/user-attachments/assets/98fc3960-b523-4c2f-87b6-4b2b06265e33" />


---

### Program 3: Image Filtering with Different Kernels
- Implemented 5 different convolution kernels: Identity, Edge Detection, Sharpen, Box Blur, Gaussian Blur
- Compared results using OpenCV's filter2D and SciPy's convolve
- Applied filters to grayscale images
- Visualized effects of each kernel type
- Demonstrated practical applications of each filter type

**Screenshot**

<img width="403" height="249" alt="image" src="https://github.com/user-attachments/assets/92a709fc-4b03-411e-b982-28d296e6af0a" />
<img width="411" height="501" alt="image" src="https://github.com/user-attachments/assets/d5225b51-df3f-40a2-adbb-847b11cde405" />
<img width="417" height="502" alt="image" src="https://github.com/user-attachments/assets/2e4fe15b-13da-47f4-b760-0c7a50dd7ad2" />
<img width="412" height="510" alt="image" src="https://github.com/user-attachments/assets/7168fb11-2aa8-4f8f-a198-75e0691686ad" />


---

### Program 4: Image Enhancement Techniques
- Implemented image negative transformation
- Created gray level slicing with background preservation
- Applied histogram equalization (both built-in and user-defined)
- Compared results of different enhancement methods
- Visualized effects on contrast and intensity distribution

**Screenshot**

<img width="558" height="204" alt="image" src="https://github.com/user-attachments/assets/5cdd1c35-8e12-4daf-9e25-30f0e1fa7aca" />
<img width="422" height="244" alt="image" src="https://github.com/user-attachments/assets/e9770fea-9ff2-4620-8081-16dc4417f492" />
<img width="468" height="171" alt="image" src="https://github.com/user-attachments/assets/17c43738-4ecf-4d22-b513-cdc7d64a8298" />
<img width="538" height="204" alt="image" src="https://github.com/user-attachments/assets/c9cda00e-d3da-4cf7-a081-5348f8dfc384" />


---

### Program 5: Image Filtering Implementation
- Implemented noise addition and removal using Gaussian noise
- Created average filter for noise reduction
- Built Gaussian blur filter for smoothing
- Developed sharpening filter for edge enhancement
- Compared built-in OpenCV functions with user-defined implementations
- Tested on Ronaldo images

**Screenshot**

<img width="185" height="342" alt="image" src="https://github.com/user-attachments/assets/eb5ed097-3103-469e-8e64-bb623d0c70ef" />
<img width="181" height="345" alt="image" src="https://github.com/user-attachments/assets/de9af07a-8f61-4cda-9556-84aafd9b4134" />
<img width="185" height="346" alt="image" src="https://github.com/user-attachments/assets/f0ed8573-63af-4f46-bd70-a6652c050d01" />
<img width="186" height="343" alt="image" src="https://github.com/user-attachments/assets/673ed115-2ef0-4980-830d-a61d526ea791" />
<img width="193" height="348" alt="image" src="https://github.com/user-attachments/assets/23ea59b6-8011-4423-ab6d-0546b4ce6674" />
<img width="240" height="391" alt="image" src="https://github.com/user-attachments/assets/cec22b87-45d2-48cf-a5fb-509a2a06b7c9" />
<img width="232" height="393" alt="image" src="https://github.com/user-attachments/assets/d8ce4e85-3de6-4c60-815a-035b7bc86d5e" />
<img width="212" height="367" alt="image" src="https://github.com/user-attachments/assets/4a624421-a178-4323-91a2-c56309ee2b19" />
<img width="207" height="375" alt="image" src="https://github.com/user-attachments/assets/02ea923a-925a-4964-85d3-5d384fb2c780" />


---

### Program 6: Frequency Domain Filtering
- Implemented Fourier Transform for frequency domain analysis
- Created ideal low-pass and high-pass filters
- Applied filters in frequency domain using FFT
- Visualized frequency domain representations
- Demonstrated effects of cutoff frequency (D0=50) on filtering
- Reconstructed images using inverse Fourier Transform

**Screenshot**

<img width="369" height="486" alt="image" src="https://github.com/user-attachments/assets/6d3dc384-8c84-4f5d-a71a-cf2f3ed58416" />
<img width="380" height="486" alt="image" src="https://github.com/user-attachments/assets/bb16e5ed-577e-472a-8a7a-191d007ff80d" />
<img width="383" height="497" alt="image" src="https://github.com/user-attachments/assets/7ab10072-5e11-4b04-84eb-4bc72b51fc77" />
<img width="387" height="267" alt="image" src="https://github.com/user-attachments/assets/448ba732-0fd9-476c-9c20-31e3cfc63dbf" />
<img width="386" height="243" alt="image" src="https://github.com/user-attachments/assets/af3b6f1f-5550-4b43-b20b-1aea149a4005" />

---

### Program 7: Nonlinear Filters
- Implemented median filter for salt-and-pepper noise removal
- Created max and min filters for morphological operations
- Developed mid-point filter for balanced smoothing
- Built alpha-trimmed mean filter for outlier removal
- Compared built-in and user-defined implementations
- Visualized effects on grayscale images

**Screenshot**

<img width="172" height="291" alt="image" src="https://github.com/user-attachments/assets/0fa25269-e331-4b8b-8bc9-93ff2ce67fb4" />
<img width="185" height="299" alt="image" src="https://github.com/user-attachments/assets/9ca42eda-9583-41a2-9d26-17eaedfa30c2" />
<img width="401" height="302" alt="image" src="https://github.com/user-attachments/assets/d82f5e2e-74e1-44fc-8788-587dff1ff328" />
<img width="407" height="309" alt="image" src="https://github.com/user-attachments/assets/3e20cf3e-4f45-47ce-9c46-d5526509c10b" />
<img width="431" height="299" alt="image" src="https://github.com/user-attachments/assets/d4618324-9cf9-4dd7-9b84-b37b8452d2c7" />
<img width="397" height="296" alt="image" src="https://github.com/user-attachments/assets/19ce1885-b281-41d5-a548-62e9ca377842" />


---

### Program 8: Edge Detection Techniques
- Implemented first-order derivative method (Sobel operator)
- Applied second-order derivative method (Laplacian operator)
- Used optimal edge detection (Canny algorithm)
- Compared results of different edge detection methods
- Analyzed trade-offs between sensitivity and noise robustness

**Screenshot**

<img width="408" height="563" alt="image" src="https://github.com/user-attachments/assets/2aeeb318-ac53-47ee-9d02-b248cb30f8bc" />


---

### Program 9: Feature Extraction Pipeline
- Created complete preprocessing pipeline (resize, grayscale, noise reduction)
- Implemented edge detection using Canny algorithm
- Extracted lines using Hough Line Transform
- Detected keypoints using ORB feature extractor
- Applied pipeline to multiple images for comparison
- Visualized edges, lines, and keypoints separately

**Screenshot**

<img width="455" height="163" alt="image" src="https://github.com/user-attachments/assets/832e11a7-003a-44e8-8a20-8b3a99ac069f" />
<img width="412" height="431" alt="image" src="https://github.com/user-attachments/assets/552d0ac2-5c14-48fd-951a-161da815a34e" />


---

### Program 10: Video Frame Analysis
- Implemented video frame extraction with configurable step size
- Separated RGB color channels for analysis
- Displayed original frame and individual color components
- Created visualization grid for color channel comparison
- Processed video file to demonstrate color decomposition

**Screenshot**

<img width="395" height="521" alt="image" src="https://github.com/user-attachments/assets/66f6912f-7e52-4e51-b88d-ff533399ef52" />
<img width="415" height="511" alt="image" src="https://github.com/user-attachments/assets/59871235-859a-4b31-91a3-97346ae6f189" />


---

### Program 11: Advanced Filtering Techniques
- Applied median filtering for noise reduction
- Implemented max and min filtering using dilation and erosion
- Used alpha-trimmed mean filtering for outlier removal
- Compared effects of different filtering techniques
- Tested on sample images with various noise types

**Screenshot**

<img width="375" height="424" alt="image" src="https://github.com/user-attachments/assets/4eb2069a-75e2-484e-a708-b7fd29e14892" />
<img width="398" height="227" alt="image" src="https://github.com/user-attachments/assets/ff428703-a85e-4f0d-b691-fe4038293500" />
<img width="383" height="428" alt="image" src="https://github.com/user-attachments/assets/a99da805-b9cc-4830-9ce1-2a6d9d349dd2" />

---

### Program 12: Comprehensive Noise Removal and Edge Detection
- Generated synthetic salt-and-pepper and Gaussian noise
- Implemented mid-point filter for noise removal
- Applied Sobel, Prewitt, and Roberts edge detection operators
- Compared performance of different edge detectors
- Analyzed trade-offs in edge detection accuracy vs noise sensitivity

**Screenshot**

<img width="158" height="162" alt="image" src="https://github.com/user-attachments/assets/a7895ad4-9902-460c-a3e3-21031f482219" />
<img width="159" height="156" alt="image" src="https://github.com/user-attachments/assets/0dac5a17-ff76-488f-92c0-fbdd0b246790" />
<img width="160" height="159" alt="image" src="https://github.com/user-attachments/assets/4ef73395-8690-499a-84c6-a72a5332899a" />
<img width="125" height="111" alt="image" src="https://github.com/user-attachments/assets/472a58ef-1b4e-4e59-8dd9-401c5bdc6aae" />
<img width="412" height="90" alt="image" src="https://github.com/user-attachments/assets/9a0631c3-551a-4fa4-88b2-d83ab2c56feb" />
<img width="619" height="174" alt="image" src="https://github.com/user-attachments/assets/af04a0d4-8218-4d15-8121-89d64369ad87" />
<img width="302" height="190" alt="image" src="https://github.com/user-attachments/assets/e4ca26a0-6220-4f3d-8bc4-640f284f5328" />




