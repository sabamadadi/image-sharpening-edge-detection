# Image Processing and Edge Detection Report

## Abstract
This study presents various image processing techniques applied to a set of five images. Methods include spatial domain sharpening using high-pass filters, Laplacian operators, and unsharp masking, as well as frequency-domain sharpening using Fourier transforms. Edge detection is performed using the Canny method. The results demonstrate enhancement of image details and effective boundary extraction.

---

## 1. Introduction
Image sharpening and edge detection are fundamental techniques in computer vision and image analysis. Sharpening improves the visibility of fine details, while edge detection identifies object boundaries. In this study, multiple methods are applied to illustrate the effects of these techniques on different types of images.

---

## 2. Materials and Methods
Five images, labeled `1.1.jpg` through `1.5.jpg`, were used for processing. The following techniques were applied:

1. **High-Pass Filtering** – Enhances edges by emphasizing high-frequency components.  
2. **Laplacian Sharpening** – Highlights areas of rapid intensity change to enhance edges.  
3. **Unsharp Masking** – Combines the original image with a blurred version to enhance details.  
4. **Frequency-Domain Sharpening** – Applies high-pass filters in the Fourier domain to emphasize high-frequency image content.  
5. **Canny Edge Detection** – Detects edges by identifying regions of rapid intensity change with adjustable thresholds.  

Processed images were visualized for qualitative assessment.

---

## 3. Results

### 3.1 Original Image 1.1

<center>
<img src="data/1.1.png" alt="Original Image 1.1" width="400"/>
<br>Figure 1: Original grayscale image 1.1
</center>

### 3.2 High-Pass Filtering

<center>
<img src="data/1.1_highpass.png" alt="High-Pass Sharpened Image" width="400"/>
<br>Figure 2: Image 1.1 after high-pass filtering
</center>

### 3.3 Laplacian Sharpening

<center>
<img src="data/1.1_laplacian.png" alt="Laplacian Sharpened Image" width="400"/>
<br>Figure 3: Image 1.1 after Laplacian sharpening
</center>

### 3.4 Unsharp Masking

<center>
<img src="data/1.1_unsharp.png" alt="Unsharp Masked Image" width="400"/>
<br>Figure 4: Image 1.1 after unsharp masking
</center>

### 3.5 Frequency-Domain Sharpening

<center>
<img src="data/1.1_frequency.png" alt="Frequency Domain Sharpened Image" width="400"/>
<br>Figure 5: Image 1.1 after frequency-domain sharpening
</center>

---

### 3.6 Edge Detection

#### Image 1.2

<center>
<img src="data/1.2.png" alt="Original Image 1.2" width="400"/>
<br>Figure 6: Original color image 1.2
</center>

<center>
<img src="data/1.2_edges.png" alt="Edges Image 1.2" width="400"/>
<br>Figure 7: Edges detected in Image 1.2 using Canny
</center>

#### Image 1.3

<center>
<img src="data/1.3.png" alt="Original Image 1.3" width="400"/>
<br>Figure 8: Original color image 1.3
</center>

<center>
<img src="data/1.3_edges.png" alt="Edges Image 1.3" width="400"/>
<br>Figure 9: Edges detected in Image 1.3 using Canny
</center>

---

### 3.7 Gray Sharpened Images

#### Image 1.4


<center>
<img src="data/1.4.png" alt="Image 1.4" width="400"/>
<br>Figure 10: Image 1.4 before sharpening
</center>


<center>
<img src="data/1.4_sharpened.png" alt="Sharpened Image 1.4" width="400"/>
<br>Figure 10: Image 1.4 after sharpening
</center>

#### Image 1.5


<center>
<img src="data/1.5.png" alt="Image 1.5" width="400"/>
<br>Figure 10: Image 1.5 before sharpening
</center>


<center>
<img src="data/1.5_sharpened.png" alt="Sharpened Image 1.5" width="400"/>
<br>Figure 11: Image 1.5 after sharpening
</center>

---

## 4. Discussion
High-pass and Laplacian filters effectively enhance edges, while unsharp masking improves detail visibility without significant artifacts. Frequency-domain sharpening demonstrates the ability to selectively enhance high-frequency components. Canny edge detection provides clear visualization of object boundaries and can be tuned with threshold adjustments. Overall, these methods improve image interpretability for further analysis.

---

## 5. Conclusion
This study demonstrates that combining spatial and frequency domain sharpening with edge detection techniques significantly enhances image details and boundary information. These methods are valuable for applications in computer vision, image analysis, and pre-processing for automated systems.
