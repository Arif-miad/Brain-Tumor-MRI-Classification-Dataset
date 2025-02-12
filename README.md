

# **Brain Tumor MRI Classification Dataset**  

## **Overview**  
The **Brain Tumor MRI Classification Dataset** is a curated collection of MRI scans categorized into four classes:  
- **Glioma**  
- **Meningioma**  
- **No Tumor**  
- **Pituitary**  

This dataset is designed for **medical image classification** and can be used in **deep learning, computer vision, and AI-driven diagnostic applications**.  

## **Dataset Structure**  
The dataset is organized into:  
- 📂 **Training Set** – Images for training deep learning models  
- 📂 **Testing Set** – Images for model evaluation and validation  

## **File Details**  
- **Version:** 1  
- **Size:** 158.6 MB  
- **Format:** PNG/JPG images  
- **Total Categories:** 4  

## **Usage**  
This dataset can be utilized for:  
✅ **Brain tumor classification using deep learning**  
✅ **Medical AI research and diagnosis automation**  
✅ **Image segmentation and feature extraction**  
✅ **Comparative analysis of machine learning models**  

## **Installation & Setup**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-repo-link.git
   ```
2. Navigate to the directory:  
   ```bash
   cd brain-tumor-mri-dataset
   ```
3. Load the dataset in Python:  
   ```python
   import os
   import matplotlib.pyplot as plt
   import cv2

   dataset_path = "path/to/dataset"
   categories = ["glioma", "meningioma", "notumor", "pituitary"]

   for category in categories:
       path = os.path.join(dataset_path, category)
       sample_image = cv2.imread(os.path.join(path, os.listdir(path)[0]))
       plt.imshow(cv2.cvtColor(sample_image, cv2.COLOR_BGR2RGB))
       plt.title(category)
       plt.show()
   ```

## **Sample Images**  
*(Include some sample images of each class here to help users visualize the dataset.)*  

## **Potential Approaches**  
- **CNN-Based Classification** (TensorFlow/Keras, PyTorch)  
- **Transfer Learning** (ResNet, VGG16, EfficientNet)  
- **Data Augmentation & Preprocessing**  

## **Related Kaggle Notebook**  
📌 **Check out the Kaggle Notebook for this dataset:** [my Kaggle Notebook Link](https://www.kaggle.com/code/arifaditra/mri-brain-tumor-detection-using-deep-learning)  

## **Connect with Me**  
🔗 **LinkedIn:** [Arif Miah](www.linkedin.com/in/arif-miah-8751bb217)  
🔗 **Kaggle:** [my Kaggle Profile](https://www.kaggle.com/arifmia)  

## **License**  
This dataset is intended for **research and educational purposes only**. Please cite if you use it in your work.  

## **Acknowledgments**  
Special thanks to researchers and the medical community contributing to AI-driven diagnostics.  

