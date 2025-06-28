# 🌱 Soil and Plant Analysis System for Agriculture

AI-powered system for identifying soil types, diagnosing plant diseases, and recommending crops and fertilizers to assist farmers with data-driven agriculture decisions.

---

## 🔍 Problem Statement
Manual identification of soil and plant health is time-consuming and error-prone. Farmers lack access to affordable diagnostic tools. This project builds an end-to-end intelligent system that:
- Classifies soil type (Alluvial, Black, Red, Clay)
- Detects plant diseases across 10+ crops
- Recommends suitable crops and pesticides

---

## 🧰 Tools & Technologies
- **Languages:** Python, Dart
- **Frameworks:** TensorFlow, Keras, Flutter
- **Libraries:** Pandas, NumPy, OpenCV
- **Deployment:** TensorFlow Lite (on-device ML)
- **IDE/Tools:** Android Studio, Google Colab, Jupyter

---

## 🧠 ML Models Used
- **Soil Classification**: Custom CNN architecture with 3 convolutional layers
- **Plant Disease Classification**: CNN trained on PlantVillage dataset (87k+ RGB images)
- **Model Optimization**: Pruning + Hyperparameter tuning

---

## 📱 Mobile App Features
- Offline soil and disease prediction via images
- Crop and pesticide recommendations
- Text and voice output (TTS enabled)

---

## 📊 Sample Architecture
```
User Image Input → Image Preprocessing → CNN Model → Prediction → Recommendation Engine → App Display
```

---

## 🌾 Dataset Details
- **Soil Dataset:** 715 training + 188 test images, 4 soil classes
- **Plant Dataset:** 87,000+ augmented images across 38 disease classes

---

## 📈 Results
| Task                        | Model Used | Accuracy  |
|-----------------------------|------------|-----------|
| Soil Classification         | CNN        | 92.6%     |
| Plant Disease Classification| CNN + Pruning | 97.5% |

---

## 🖼️ Screenshots
![image](https://github.com/user-attachments/assets/5de0e8ae-2185-446e-8358-dda02db4dffd)
![image](https://github.com/user-attachments/assets/7ee0a9a5-e579-4b97-a38c-d2838dc308c7)
![image](https://github.com/user-attachments/assets/099aba2b-2a70-4d28-a753-4dcd212191e0)
![image](https://github.com/user-attachments/assets/7af8cfa7-e957-40f2-95d9-192a8c31c447)
![image](https://github.com/user-attachments/assets/7174a74d-c351-4895-9842-a628ddf72365)
![image](https://github.com/user-attachments/assets/0360da7b-b730-45df-9422-6e1fbef24be5)



---

## 📂 Project Structure
```
soil-plant-analysis-system/
├── data/                  # Soil and leaf image datasets
├── models/                # Trained CNNs (SoilNet, DiseaseNet)
├── notebooks/             # Jupyter/Colab training scripts
├── app/                   # Flutter mobile app source
├── images/                # UI screenshots
└── README.md              # Project overview
```

---

## 🚜 Future Scope
- Real-time weather integration
- Soil nutrient analysis
- Voice-based farmer chatbot
- IoT sensor data integration

---

## 👨‍💻 Contributors
- Yanamandra Satya Karthik
- Ramachandra Rao Chikkala
- Uttarala Chetan Rama Kumar
- Chitturi Rohith Sai

---

## 📬 Contact
- ✉ Email: [satyakarthik.y@gmail.com](mailto:satyakarthik.y@gmail.com)
