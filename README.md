# vocalis-AI

# 🎤 Vocalis-AI

**Vocalis-AI** is an AI-powered web application that validates and predicts the **emotion of animal sounds** using cutting-edge machine learning techniques and interactive frontend design. It provides **real-time emotion predictions** with confidence scores and generates **human-like phrases** based on the detected emotion.

🌐 **Live Demo:** [https://vocalis-ai.onrender.com](https://vocalis-ai.onrender.com)

---

## 🚀 Features

- 🎯 Emotion Detection from Animal Sounds
- 📂 Audio Upload + Real-time Recording Support
- 🔁 Real-time Processing & Feedback
- 🔍 Audio-Animal Match Validation using LightGBM
- 💡 Human-like Phrase Generation
- 🌙 Dark Mode Toggle
- 📈 High Model Accuracy & Confidence Score Display

---

## 🖼️ Frontend Overview

- **Tech Stack:** HTML, CSS, JavaScript
- **Audio Input Options:**
  - Upload `.wav` or `.mp3` files
  - Record audio directly in-browser
- **Dark Mode:** Toggle available

---

## 🐾 Animal Match Validation

- User selects a target animal from a dropdown.
- Audio filename must match format: `animal_*.wav`
- Validation handled by a **LightGBM** model.
- If mismatched:
  ```json
  {
    "emotion": "Unknown or Invalid"
  }
