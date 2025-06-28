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
![Home UI](images/home_ui.png)
![Soil Prediction](images/soil_predict.png)
![Disease Prediction](images/disease_predict.png)
![Crop Recommendation](images/crop_recommend.png)

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
