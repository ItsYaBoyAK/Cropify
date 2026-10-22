# 🌱 Crop Disease Detection

A simple application for detecting diseases in **Rice**, **Wheat**, **Tomato**, and **Cotton** leaves and giving solutions using TensorFlow models.

-------
## Features
- Uses MobileNetV2 for image classification
- Models trained with Kaggle datasets & Teachable Machine
- Flask-based GUI built with PyWebGUI

## Technologies Used
- Python
- MobileNetV2
- TensorFlow / Keras
- Flask
- PyWebGUI
- HTML, CSS, JavaScript
- Google Colab for training

## 📂 Project Structure
├── models/<br>
│ ├── cotton_model.tflite<br>
│ ├── rice_model.tflite<br>
│ ├── tomato_model.tflite<br>
│ └── wheat_model.tflite<br>
├── static/<br>
│ ├── display_images/<br>
│ └── user_files/ <br>
├── templates/ <br>
│ ├── cotton.html<br>
│ ├── crops.html<br>
│ ├── home.html<br>
│ ├── rice.html<br>
│ ├── tomato.html<br>
│ └── wheat.html<br>
├── main.py <br>

## ⚙️ How It Works
1. User uploads a leaf image.
2. Model predicts disease & displays confidence score.
3. Displays a short solution for treatment.

---

## 🙌 Acknowledgements
- [TensorFlow Lite](https://www.tensorflow.org/lite) 
- [Flask](https://flask.palletsprojects.com/) 
- [Google Teachable Machine](https://teachablemachine.withgoogle.com/) 
- [Google Colab](https://colab.research.google.com/) 
- [Kaggle](https://www.kaggle.com/) 


---

## 👥 Contributors

- [Shiva Vijai](https://github.com/Shiva-Vijai)
- [Akshath](https://github.com/ItsYaBoyAK)
- [Shreyan]()
- [Adarsh]()
