# CSCI611_Spring25_SaiAravindReddy_Katteragandla

# CSCI 611 - Assignment 2: Image Processing & CNN Implementation

# Overview
This repository contains the implementation of **image filtering** and **deep learning with CNN** as part of **CSCI 611 - Assignment 2**. 

The project is divided into two main parts:
1. **Image Processing**: Edge detection, blurring, scaling, and corner detection using OpenCV.
2. **Convolutional Neural Network (CNN)**: Training a CNN on the CIFAR-10 dataset for image classification using PyTorch.

---

# 📂 Repository Structure

```
📂 CSCI-611_A2/
│── 📂 build_cnn/ 
│   ├── build_cnn.ipynb           # Jupyter Notebook for CNN implementation
│   ├── cifar_data.png             # Sample CIFAR-10 data visualization
│── 📂 image_filtering/ 
│   ├── image_filtering.ipynb      # Jupyter Notebook for image processing tasks
│   ├── building2.jpg              # Input image used for filtering operations
│── cnn_architecture.png           # CNN Model Architecture Diagram
│── loss_plot.png                  # Training loss vs validation loss plot
│── 611_A2.docx                    # Final report for the assignment
│── README.md                      # This ReadMe file
```

---

## Installation & Setup

### Clone the Repository
To download and use this project, clone this repository to your local machine:

```sh
git clone https://github.com/<skatteragandla>/CSCI611_Spring25_SaiAravindReddy_Katteragandla.git
cd Assignment 2

---

### Install Dependencies

Ensure you have **Python 3.x** installed. The required dependencies can be installed using:


If you are using **Google Colab**, install required packages directly in the notebook:

```python
!pip install torch torchvision matplotlib numpy opencv-python
```

---

## How to Run the Code

###  Running Image Processing Code (OpenCV)
1. Navigate to the **`image_filtering/`** directory.
2. Open `image_filtering.ipynb` in **Google Colab** or **Jupyter Notebook**.
3. Run all the cells to apply various **image processing techniques**, including:
   - **Edge Detection**
   - **Blurring**
   - **Scaling**
   - **Corner Detection**

---

### Running CNN Training & Evaluation (PyTorch)
1. Navigate to the **`build_cnn/`** directory.
2. Open `build_cnn.ipynb` in **Google Colab** or **Jupyter Notebook**.
3. Run all cells to:
   - **Load the CIFAR-10 dataset**
   - **Define the CNN architecture**
   - **Train the model**
   - **Evaluate model performance on test data**
   - **Visualize results**

---

## Results & Findings

### 🔹 CNN Model Architecture
- The architecture of the trained CNN model is saved in `cnn_architecture.png`.

### 🔹 Training & Validation Loss
- The **loss graph** is saved in `loss_plot.png`, showing the learning progress of the model.

---

## 📜 Submission Details
- The **final report (`611_A2.docx`)** summarizes results, implementation details, and findings.
- The repository follows the **assignment guidelines**.
- **Visualizations (`cnn_architecture.png` and `loss_plot.png`)** illustrate model performance.

---
