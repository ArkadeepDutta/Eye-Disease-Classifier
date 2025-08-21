# Eye Disease Classifier using CNN

Early detection of eye disorders is crucial to prevent vision loss and enable timely treatment. Diseases like **Diabetic Retinopathy**, **Glaucoma**, and **Cataracts** often show little to no symptoms in their early stages, making automated screening an important tool.  
This project uses **Deep Learning (CNN)** to classify retinal images into four categories: *Normal, Cataract, Diabetic Retinopathy, and Glaucoma*.

---

## 📂 Dataset
The dataset contains approximately **1000 images per class** for:
- Normal
- Cataract
- Diabetic Retinopathy
- Glaucoma  

Images are collected from public sources like *IDRiD, HRF, and Ocular Recognition*.  
🔗 [Download Dataset from Kaggle](https://www.kaggle.com/datasets/gunavenkatdoddi/eye-diseases-classification)

---

## 🖼️ Sample Images
- **Cataract** – Clouding of the eye lens causing blurred vision  
  <img src="https://github.com/SinaRaoufi/Eye-Diseases-Classification/blob/master/samples/cataract.jpg" width="128" height="128" />

- **Diabetic Retinopathy** – Retinal blood vessel damage due to diabetes  
  <img src="https://github.com/SinaRaoufi/Eye-Diseases-Classification/blob/master/samples/diabetic_retinopathy.jpeg" width="128" height="128" />

- **Glaucoma** – Optic nerve damage, often linked to high eye pressure  
  <img src="https://github.com/SinaRaoufi/Eye-Diseases-Classification/blob/master/samples/glaucoma.jpg" width="128" height="128" />

- **Normal Retina** – Healthy retinal structure  
  <img src="https://github.com/SinaRaoufi/Eye-Diseases-Classification/blob/master/samples/normal.jpg" width="128" height="128" />

---

## 🧠 Model Architecture
The classification model is a **Convolutional Neural Network (CNN)** built with:
- `Conv2D` layers → extract spatial features  
- `ReLU` activations → non-linearity  
- `MaxPooling` layers → down-sampling  
- `Fully Connected layers` → classification into 4 categories  

---

## ⚙️ Installation

Clone this repository:
```bash
git clone https://github.com/your-username/eye-disease-detection.git
cd eye-disease-detection
