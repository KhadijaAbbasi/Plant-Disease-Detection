# Plant-Disease-Detection

This project uses a **Convolutional Neural Network (CNN)** in PyTorch to detect plant leaf diseases.  
The dataset is taken from Kaggle: [New Plant Diseases Dataset](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset).

---

# Project Workflow
1. **Dataset** – Downloaded from Kaggle (train/valid/test split).  
2. **Data Preprocessing** – Resize, normalize, and apply augmentations.  
3. **Model** – Custom CNN built with PyTorch.  
4. **Training** – Trained on the dataset with accuracy tracking.  
5. **Evaluation** – Tested on unseen images.  

---

## Tech Stack
- Python  
- PyTorch  
- Torchvision  
- Matplotlib, Seaborn  

---

## Results
- The CNN model was able to classify plant diseases with good accuracy.  
- Further improvements can be made by using transfer learning (e.g., ResNet).  
