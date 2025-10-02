#  COVID-19 Chest X-Ray Classification  

This project uses **Deep Learning (Transfer Learning with VGG16)** to classify **COVID-19, Bacterial Pneumonia, and Normal chest X-rays**.  
The model is trained on a publicly available chest X-ray dataset and deployed as a **Flask web app** for real-time predictions.  

---

##  Project Overview  
- Detects **COVID-19**, **Bacterial Pneumonia**, and **Normal** chest X-rays.  
- Built with **TensorFlow / Keras** using **VGG16 pretrained model**.  
- Achieved **96%+ validation accuracy** with fine-tuning.  
- Deployed using **Flask + Ngrok** for live predictions.  

---

## Dataset  
- Public dataset of Chest X-rays (COVID-19, Pneumonia, Normal).  
- Data split into **train**, **validation**, and **test** sets.  
- Preprocessing:  
  - Resize images to **64x64 RGB**.  
  - Normalize pixel values `[0,1]`.  
  - Data augmentation: rotation, zoom, flips.  

---

##  Tech Stack  
- **Python 3.8+**  
- **TensorFlow / Keras**  
- **Flask** (for deployment)  
- **Ngrok** (for public URL)  
- **NumPy, Pandas, Matplotlib**  

---

## Model Training  

1. Fine-tuned VGG16 (transfer learning) → **96% accuracy**.  

 Training Parameters:  
- Optimizer: **Adam** (lr=1e-4)  
- Loss: **Categorical Crossentropy**  
- Batch size: **32**  
- Epochs: **10**  

---

## Results  
- **Validation Accuracy**: ~96%  


