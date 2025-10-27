# Edge Detection using OpenCV (Google Colab)

This project demonstrates various **edge detection techniques** using **OpenCV** and **Matplotlib** — all implemented and visualized directly in **Google Colab**.  
It allows you to upload an image interactively, process it through multiple edge detectors, and visualize & save the results for comparison.

---

## 📘 Table of Contents
- [Overview](#overview)
- [Techniques Implemented](#techniques-implemented)
- [Features](#features)
- [Setup & Usage](#setup--usage)
  - [Run on Google Colab](#run-on-google-colab)
- [Output Examples](#output-examples)
- [Project Structure](#project-structure)
- [Code Explanation](#code-explanation)
- [Dependencies](#dependencies)
- [References](#references)
- [License](#license)

---

## 🔍 Overview

Edge detection is one of the most important steps in image processing and computer vision.  
It helps identify object boundaries, extract structural information, and simplify further image analysis.

This notebook implements **three major edge detection algorithms** — Sobel, Laplacian, and Canny — and compares their output side by side for easy visualization and understanding.

---

## ⚙️ Techniques Implemented

| Technique | Description | Output Characteristics |
|------------|--------------|-------------------------|
| **Sobel Operator** | Computes gradient magnitude using horizontal and vertical derivatives. | Detects edges based on intensity changes; sensitive to noise. |
| **Laplacian Operator** | Uses second-order derivatives to find regions of rapid intensity change. | Produces sharper edges but can enhance noise. |
| **Canny Edge Detector** | Multi-stage algorithm including gradient calculation, non-maximum suppression, and hysteresis thresholding. | Produces smooth and accurate edge maps; robust to noise. |

---

## 🌟 Features

✅ Upload your own image directly in Colab (.jpg or .png)  
✅ Automatically resizes and converts the image to grayscale  
✅ Generates edge maps using **Sobel**, **Laplacian**, and **Canny**  
✅ Displays a 4-panel visual comparison using Matplotlib  
✅ Saves all outputs (individual and combined) in a local directory  
✅ Works entirely inside Google Colab — no setup required  

---

## 🚀 Setup & Usage

### ▶️ Run on Google Colab

1. **Open your Google Colab notebook** and upload the `.py` file or copy-paste the code.
2. Run the cells sequentially.
3. When prompted:
   - Upload an image (`.jpg` or `.png`).
4. Wait for processing to complete.
5. View and download results in the generated `/edge_outputs` folder.

---

### 🧾 Output Examples

After running, you will get four visual outputs:

| Visualization | Description |
|----------------|--------------|
| **Original** | The uploaded input image resized to 512x512 |
| **Sobel Edges** | Gradient-based edge map |
| **Laplacian Edges** | Sharper edges using 2nd-order derivatives |
| **Canny Edges** | Clean, well-defined edges with noise suppression |
