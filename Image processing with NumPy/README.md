# 🌈 Image Processing with NumPy — Color Channel Frequency Distribution

## Project Overview
This project demonstrates **fundamental image processing techniques** using **NumPy** by analyzing the **frequency distribution of pixel intensities** in a colorful image (a rainbow photograph).

The analysis focuses on understanding how the **Red, Green, and Blue (RGB) color channels** contribute to the image’s overall appearance. All computations are fully **vectorized using NumPy**, avoiding explicit Python loops to ensure efficiency and clarity.

---

## Objective
To analyze and visualize RGB color channel distributions in an image using vectorized NumPy operations, gaining insights into pixel intensity patterns and demonstrating core image processing concepts.

---

## Data Source
- **rainbow.png**
  - A colorful image used to analyze RGB pixel intensity distributions
  - Serves as input for channel extraction and histogram computation

---

## Methods & Tools Used
- Image loading and visualization
- RGB channel extraction
- Histogram computation using NumPy
- Normalization of frequency distributions
- Statistical analysis of pixel intensities
- Data visualization using plots

---

## Programming Environment
- Python 3.12
- Jupyter Notebook

---

## Libraries Used
- **Numerical Computing:** NumPy  
- **Image Handling & Visualization:** Matplotlib  

---

## Workflow 

1. Load and display the input image  
2. Extract Red, Green, and Blue (RGB) color channels  
3. Visualize individual color channels  
4. Compute frequency distributions (histograms) for each channel  
5. Normalize histograms for comparative analysis  
6. Visualize color channel distributions  
7. Compute summary statistics (mean, variance, etc.) for pixel intensities  

---

## Project Structure
```text
├── Image_processing_with_numpy.ipynb   # Complete image analysis workflow
├── rainbow.png                         # Input image
├── README.md                           # Project documentation
└── LICENSE                             # MIT License
```

---

## Results & Insights
- RGB channels show distinct intensity distribution patterns
- Red, Green, and Blue channels contribute differently to the overall color composition
- Histogram normalization enables fair comparison between channels
- Vectorized NumPy operations provide efficient and readable image analysis
- Demonstrates how simple statistical methods can reveal image characteristics

---

## Practical Applications
- Foundational image processing and computer vision tasks
- Feature extraction for image classification
- Color analysis for design and photography
- Preprocessing step for machine learning and deep learning pipelines
- Educational demonstration of NumPy vectorization

---

## How to Run This Project
1. Clone the repository: *git clone https://github.com/yourusername/your-repo-name.git*
2. Open the notebook: *jupyter notebook Image_processing_with_numpy.ipynb*
3. Run all cells sequentially to reproduce the analysis

---

## Future Enhancements
- Implement Histogram Equalization to enhance image contrast
- Compare color distributions across multiple images
- Build a simple color-based image classifier using histogram features
- Extend analysis to different color spaces (HSV, LAB)

### License
This project is licensed under the MIT License.

**Ethical Use Notice:**
This project is intended for educational, research, and professional learning purposes.

Misrepresentation of authorship or deceptive use is unethical. Attribution is required under the MIT License.
