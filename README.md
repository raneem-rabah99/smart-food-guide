# Smart Food Guide – Health Chatbot & Food Recognition 🍽️🧠

A Flutter-based **health assistant application** that combines a **disease-aware chatbot**
with a **CNN-based food recognition model**, built from scratch.
The system focuses on **Syrian cuisine** and provides **dietary and calorie guidance**
based on recognized foods and health conditions.

> ⚠️ Disclaimer: This project provides educational guidance only and is not a substitute for medical advice.

---

## ✨ Key Features

- 🩺 **Disease-Based Health Chatbot**
  - Chat interface for asking about diseases
  - Personalized food recommendations
  - Clear guidance on:
    - ✅ What to eat
    - 🚫 What to avoid

- 🧠 **Food Recognition Model (CNN)**
  - Custom **Convolutional Neural Network built from scratch**
  - Recognizes Syrian and regional foods
  - High-confidence predictions for supported dishes

- 📸 **Image-Based Meal Analysis**
  - Upload a meal image
  - Predict food type with confidence score
  - Display calories and dietary information

- 💾 **Saved Conversations**
  - Store chat history and previous analyses
  - Review past recommendations

---

## 🧠 Model Details

- **Model type:** Convolutional Neural Network (CNN)
- **Built from:** Scratch (no pre-trained models)
- **Input:** Food images
- **Output:** Food class + confidence score
- **Focus:** Syrian and mixed cuisine

### Example Predictions
| Dish | Confidence |
|-----|------------|
| Warak Enab | 99.69% |
| Fattoush | 80.82% |
| Molokhia | 100% |

_Sample prediction images are shown below._

---

## 🗂 Dataset

- Custom-built dataset focused on **Syrian dishes**
- Images collected and curated manually
- Dataset structured specifically for CNN training
- Balanced classes to improve generalization

> The dataset was designed and refined to match the requirements of CNN-based image classification.

---

## 🧪 Experiments

- Conducted **8 training experiments**
- Tested different:
  - Network depths
  - Filter sizes
  - Learning rates
  - Regularization techniques
- Final model selected based on:
  - Accuracy
  - Stability
  - Confidence scores

---

## 🛠 Tech Stack

- Flutter / Dart
- Dio (HTTP networking)
- Python (model training)
- CNN (custom architecture)
- Local storage for saved chats

---

## ▶️ Demo

- 🎥 Demo video: `demo/demo.mp4`
- 📷 Screenshots & model predictions: `demo/images/`

