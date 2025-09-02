# RenalCancerDetection
This project is a **Deep Learning-based diagnostic system** that detects whether a kidney CT scan image is **Normal** or contains a **Tumor**.The application uses **Streamlit** as the user interface, allowing users to **drag & drop CT scan images** for instant prediction.

## Features
- Upload CT scan images through a simple **Streamlit UI**.
- Classifies images as **Tumor** or **Normal**.
- Built using a **Hybrid CNN Model** (ResNet50 + Xception) with Transfer Learning.
- Achieved **98% diagnostic accuracy** on a dataset of **10,000 medical images**.

## Model Architecture
- **Backbones:** ResNet50 + Xception  
- **Framework:** TensorFlow / Keras  
- **Techniques Used:**  
  - Transfer Learning (for faster convergence)  
  - Fine-tuning for medical image adaptation  
  - Optimized preprocessing pipeline

## Dataset
- **Source:** [Kaggle Renal CT Scan Dataset](https://www.kaggle.com/)  
- Contains **10,000 images** (Normal & Tumor cases).

## Tools & Libraries
- Python, Jupyter Notebook  
- TensorFlow / Keras  
- Streamlit (for UI)  
- NumPy, Pandas, OpenCV, Matplotlib

## Results
Accuracy: 98%
Loss curves and accuracy plots available in the notebook.

## Future Improvements
Deploy as a link
Add explainability using Grad-CAM.

## Author
Hariharan R
Amrith P

 
