# 🩺 Skin Cancer Prediction using CNN

This project is a web-based application that uses a Convolutional Neural Network (CNN) to predict whether a skin lesion is **Benign** or **Malignant**. Built with **TensorFlow** and deployed via **Streamlit**, it provides an interactive interface for uploading images, making predictions, and downloading a customized PDF report.

---

## 🚀 Features

- 🔍 **Image Classification** using a trained CNN
- 📄 **PDF Report Generation** with prediction and homeopathic remedy suggestions
- 🧑‍⚕️ User-friendly UI built with **Streamlit**
- 🖼️ Accepts `.jpg`, `.jpeg`, `.png` images
- 📅 Auto-includes date and user input (Name, Age, Address)
- 💊 Recommendations for treatment if malignant

---

## 🧠 Model Information

- **Input Shape**: 150x150x3 RGB images
- **Framework**: TensorFlow/Keras
- **Trained Model File**: `Skin_Cancer_main.keras`
- **Output**: Binary Classification (Benign or Malignant)

---

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/Bhavya773-coder/Skin_Cancer_CNN.git
cd Skin_Cancer_CNN

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt
streamlit run app.py
```
📁 Project Structure

Skin_Cancer_CNN/
│
├── app.py                  # Main Streamlit app
├── Skin_Cancer_main.keras  # Trained CNN model
├── output_reports/         # Generated PDF reports
├── requirements.txt
├── README.md
└── .gitignore
🧾 Sample PDF Report

The PDF includes:

Patient details
Prediction result and confidence score
Suggested homeopathic remedies (for Malignant results)
Timestamp of diagnosis
![image](https://github.com/user-attachments/assets/35f61ec3-8af5-455b-9de2-97f59e3a08e9)
<img width="897" alt="Screenshot 2025-04-24 at 2 53 03 PM" src="https://github.com/user-attachments/assets/a315cb95-a217-46d2-963d-8bf58cbe6e31" />



🛡️ Disclaimer

This tool is intended for educational and experimental use only. It is not a replacement for professional medical diagnosis. Always consult a dermatologist for accurate evaluation.

📬 Contact

Author: Bhavya
📫 GitHub: Bhavya773-coder
📩 Email: mashrubhavya5@gmail.com



