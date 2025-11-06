# Cartoon Image Generator with OpenCV

##  Project Overview
**Cartoon Image Generator with OpenCV** is a Python-based project that transforms real-life photos into cartoon-style images using advanced image processing techniques.  
The project leverages **OpenCV**, **NumPy**, **Matplotlib**, **EasyGUI**, and **Tkinter** to perform operations like grayscale conversion, edge detection, bilateral filtering, and masking — all to create a smooth and visually pleasing cartoon effect.

Users can easily upload an image, view each transformation step, and save the final cartoonified version through a simple graphical interface.

---

##  Technologies Used

| Library | Purpose |
|----------|----------|
| **OpenCV (cv2)** | Image processing and filtering |
| **NumPy** | Numerical operations on image arrays |
| **Matplotlib** | Displaying processed images |
| **EasyGUI** | Simple image upload dialog |
| **Tkinter** | GUI interface for saving images |
| **Pillow (PIL)** | Image handling and display support |

---

##  Workflow Steps

1. **Upload Image** – Select an image using a file dialog.  
2. **Convert to Grayscale** – Simplify image data for processing.  
3. **Apply Median Blur** – Smoothen the image and reduce noise.  
4. **Detect Edges** – Use adaptive thresholding to identify outlines.  
5. **Apply Bilateral Filter** – Retain edge sharpness while smoothing colors.  
6. **Combine Results** – Mask edges over the smoothed image to form the cartoon.  
7. **Save Final Output** – Store the generated cartoon image locally.

---
