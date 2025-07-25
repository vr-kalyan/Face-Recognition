# Face Recognition with Custom Dataset (Google Colab)

This project demonstrates face recognition using a custom dataset of images. It uses **TensorFlow** and **Keras** in **Google Colab** to train a deep learning model for face classification. The dataset is user-uploaded (typically in ZIP format) and is used to build a robust face recognition system.

---

## 🔍 Project Highlights

- Face recognition with your own image dataset
- Image classification using Convolutional Neural Networks (CNN)
- Easy dataset upload and training in Google Colab
- Visualized accuracy/loss graphs during training
- Prediction on uploaded test image with visual comparison
- Easily extendable to real-time webcam face recognition

---

## ▶️ How to Run This Project in Google Colab

1. **Open Colab:**
   - Visit [https://colab.research.google.com](https://colab.research.google.com)

2. **Upload the Notebook:**
   - Click `File > Upload Notebook` and select the `.ipynb` file

3. **Upload Your Dataset:**
   - Prepare a ZIP file of your face dataset
     ```
     face_images/
       ├── person1/
       │    ├── img1.jpg
       │    ├── img2.jpg
       ├── person2/
       │    ├── img1.jpg
       │    ├── img2.jpg
     ```
   - Use `files.upload()` in Colab to upload the ZIP file

4. **Train the Model:**
   - Run the notebook cells step-by-step
   - Model will be trained and show training accuracy/loss

5. **Make Predictions:**
   - Upload a test face image
   - The model will show the uploaded image and the best match from the dataset


## 🤖 Model Accuracy

> **Note:** The model’s accuracy can be improved by:
- Training with **more images per person**
- Using **clear and well-lit** facial images
- Including images with **varied angles and expressions** for robustness

---
