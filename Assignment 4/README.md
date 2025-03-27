# Assignment 4: Style Transfer  
**Course:** CSCI 611 - Spring 2025  
**Author:** Sai Aravind Reddy Katteragandla  

---

## 📌 Project Overview
This project implements **Neural Style Transfer** using a pre-trained VGG19 model. The objective is to generate a new image that retains the *content* of one image while applying the *style* of another. The implementation follows the provided `Style_Transfer_Exercise.ipynb` notebook from the course materials.

The final results are obtained by optimizing a target image to minimize both content loss and style loss using deep feature representations from the VGG19 model.

---

## 🧪 Assignment Breakdown

- **Part 1 [60%]:** Complete the provided notebook and all TODOs using the VGG19 model to extract content and style representations.
- **Part 2 [30%]:** Experiment with different hyperparameters (e.g., style weight, number of steps) and compare the visual results.
- **Part 3 [10%]:** Summarize the implementation, findings, and observations in a separate report PDF.

---

## ⚙️ Instructions to Run the Project

### 📁 Environment
This project is designed to be run on **Google Colab** for easy execution and GPU acceleration.

### ▶️ Steps to Execute

1. **Open the Colab Notebook**  
   Launch the notebook `Style_Transfer_Exercise.ipynb` in Google Colab.

2. **Upload Your Images**  
   - Use the Colab **sidebar file uploader**  
   or  
   - Mount your **Google Drive** and load images from a folder.

3. **Execute Notebook Cells in Order**  
   - Load VGG19 model  
   - Load and preprocess content and style images  
   - Define Gram Matrix, content and style loss functions  
   - Run optimization loop to generate the stylized target image

---




