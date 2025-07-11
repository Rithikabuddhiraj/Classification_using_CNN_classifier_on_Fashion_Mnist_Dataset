# 🧥 Clothing Item Classification using CNN | Flask-Deployed Fashion Image Recognition

## 📌 Overview

This project implements a Convolutional Neural Network (CNN) to classify fashion items from grayscale images in the Fashion MNIST dataset. The model is trained to recognize clothing categories such as shirts, shoes, bags, and more. A user-friendly Flask web interface allows real-time image upload and prediction.

## 🚀 Key Features

* 🔍 Built and trained a CNN model using TensorFlow & Keras.
* 🧠 Achieved high classification accuracy on unseen fashion item images.
* 🌐 Integrated Flask to deploy the model as a web-based application.
* 🖼️ Allows users to upload fashion item images for instant prediction.
* 📊 Visualizes model performance with loss/accuracy plots.

## ⚙️ Tech Stack

* **Frontend**: HTML/CSS (within Flask templates)
* **Backend**: Python, Flask
* **ML/DL**: TensorFlow, Keras
* **Dataset**: Fashion MNIST
## 🛠️ How to Use

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Rithikabuddhiraj/Classification_using_CNN_classifier_on_Fashion_Mnist_Dataset.git
   cd Classification_using_CNN_classifier_on_Fashion_Mnist_Dataset
   ```

2. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**

   ```bash
   python app.py
   ```

4. **Visit the Web App**
   Open `http://127.0.0.1:5000` in your browser.

## 🖼️ Sample Output

* Upload an image of a fashion item (28x28 grayscale).
* Get real-time predicted label with confidence score.

## 📂 Project Structure

* `model.py` – Model architecture and training script.
* `app.py` – Flask app for serving the model.
* `templates/` – HTML files for UI.
* `static/` – (Optional) for custom CSS or image assets.

## ✅ Status

> 📌 Completed and deployed locally. Ready for integration on cloud platforms if needed.
