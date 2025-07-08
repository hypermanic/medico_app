# 💊Medico App AI Symptom Checker + Hospital Finder

This is a Streamlit-based AI-powered medical assistant that helps users:
- Get likely **disease predictions** based on symptom descriptions.
- Receive **treatment suggestions** and **diet recommendations**.
- Locate **nearby hospitals** based on a user-provided pincode or area.

Powered by [SentenceTransformers](https://www.sbert.net/) and pre-encoded symptom embeddings, this app provides a fast and interactive experience for basic health inquiries.

---

## 🚀 Features

- 🧠 **AI-Powered Symptom Checker**: Matches your symptom description with a medical dataset using semantic similarity.
- 💊 **Treatment & Diet Advice**: Suggests treatments and dietary guidance for the identified condition.
- 🩺 **BP & Age Relevance**: Adjusts the prediction if the disease is linked to blood pressure or age.
- 🏥 **Nearby Hospital Finder**: Quickly finds the nearest hospital using pincode or location.
- ⚠️ **Emergency Warnings**: Detects dangerously high or low BP readings and shows an alert.

---

## 📂 File Structure
├── app.py   # Main Streamlit application

├── Diseases_Symptoms_with_Diet.csv # Dataset for symptom-disease-treatment-diet

├── hostwithpinandloco.csv # Hospital location and pincode dataset


---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/ai-symptom-checker.git
cd ai-symptom-checker
🧠 Model

    Model Used: all-MiniLM-L6-v2

    Why: Fast and lightweight transformer model ideal for semantic text similarity tasks.
