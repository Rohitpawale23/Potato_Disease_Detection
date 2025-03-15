# 🌿 Potato Disease Detection

** Check our Hete--> https://potato-disease-detection-032.streamlit.app/

## 🔍 Overview

An **AI-powered system** designed to detect and classify potato leaf diseases using **deep learning**. The model categorizes leaves into:
- ✅ Healthy
- 🍂 Early Blight
- 🍃 Late Blight

Traditional methods are slow and error-prone. This project provides a **fast, automated, and accurate** solution.

## 🚀 Features

✅ **Deep Learning Model:** CNN-based classification.
✅ **Web UI:** Built with Streamlit.
✅ **Automatic Model Loading:** Downloads if unavailable.
✅ **Instant Predictions:** Upload an image & get results.


## 🛠 Technologies Used

🔹 Python, TensorFlow, Keras
🔹 Streamlit (Web UI)
🔹 NumPy, PIL (Image Processing)
🔹 gdown (Model Download)

## 📌 Installation
Ensure Python is installed, then run:
```bash
pip install streamlit tensorflow numpy gdown pillow
```

## ▶️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/Potato_Disease_Detection.git
   cd Potato_Disease_Detection
   ```
2. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```
3. Open **http://localhost:8501** in your browser.

## 🏗 Project Structure
```
Potato_Disease_Detection/
│── app.py                # Main application file
│── trained_plant_disease_model.keras # Pre-trained model
│── Disease.jpg           # Sample image for UI
│── requirements.txt      # Dependencies
└── README.md             # Documentation
```

## 📊 How It Works

1. **Load Model:** Checks for a pre-trained model or downloads it.
2. **Upload Image:** Users upload a potato leaf image.
3. **Prediction:** The CNN model classifies the disease.
4. **Display Result:** Shows the detected disease type.

## 📈 Future Enhancements

- 🔼 Improve accuracy with more training data.
- 📸 Add real-time camera support.
- 🌾 Expand detection to other crops.


🚀 **Transforming Agriculture with AI!** 🌱

