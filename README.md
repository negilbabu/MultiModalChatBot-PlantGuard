<h1 align="center">
  PlantGuard | Multimodal AI Pathology Assistant 🌿🤖
</h1>

<p align="center">
  <strong>Bridging Computer Vision and Conversational AI for precision agriculture with an interactive Gradio interface.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/MSc_AI-Academic_Project-blue?style=for-the-badge" alt="Academic Context" />
  <img src="https://img.shields.io/badge/UI-Gradio-FFBB00?style=for-the-badge&logo=gradio&logoColor=black" alt="Gradio" />
  <img src="https://img.shields.io/badge/Architecture-EfficientNet--B0-success?style=for-the-badge" alt="EfficientNet" />
  <img src="https://img.shields.io/badge/Keras-Deep_Learning-D00000?style=for-the-badge&logo=keras&logoColor=white" alt="Keras" />
</p>

---

## 📖 Project Overview

**PlantGuard** is a production-oriented multimodal chatbot developed as part of my **MSc in Artificial Intelligence at BSBI**. The system addresses the gap between raw visual data and user-friendly diagnostics. By integrating a fine-tuned **EfficientNet-B0** Convolutional Neural Network (CNN) with a **Gradio-powered interactive interface**, PlantGuard enables users to diagnose plant diseases simply by uploading photos of distressed leaves and receiving structured, actionable treatment advice.

## 🚀 Architectural Highlights

### 👁️ Computer Vision Engine
- **Transfer Learning:** Leverages a pre-trained **EfficientNet-B0** backbone. This architecture uses compound scaling to achieve higher accuracy than traditional models while remaining computationally efficient for real-time inference.
- **Image Pre-processing:** Automated pipeline for resizing, normalization, and data augmentation to improve model robustness against real-world photo variations.
- **Optimized Weights:** Includes a serialized `.keras` model ready for high-speed inference in production-like environments.

### 💬 Interactive UI & Logic (Gradio)
- **Seamless UX:** Built with **Gradio** to provide an intuitive drag-and-drop interface for image uploads and a responsive chat window for diagnostic feedback.
- **Multimodal Flow:** The system captures visual features from the EfficientNet head and merges them with NLP-driven logic to provide tailored advice on treatment, prevention, and environmental factors.

---

## 🛠️ Technology Stack

| Layer | Technology | Key Usage |
| :--- | :--- | :--- |
| **Interactive UI** | **Gradio** | Web-based interface for image processing and chat. |
| **Deep Learning** | **Keras / TensorFlow** | Model architecture, training, and fine-tuning. |
| **Backbone** | **EfficientNet-B0** | SOTA compound-scaled feature extraction. |
| **Data Science** | **NumPy / Pandas** | Data manipulation and result structuring. |
| **Environment** | **Jupyter Notebook** | End-to-end research, training, and evaluation. |

---

## 🛡️ Key Technical Features

- **High-Accuracy Classification:** EfficientNet-B0 provides a superior baseline for distinguishing between healthy leaves and multiple disease categories (e.g., Rust, Blight, Powdery Mildew).
- **Real-time Diagnosis:** Interactive interface allows for instant feedback from leaf image upload to disease classification.
- **Scalable Architecture:** Designed with modularity, allowing for easy expansion to new plant species or integration with more complex LLM backends.

---

## 🚀 Getting Started

### Prerequisites
* Python 3.9+
* TensorFlow 2.x
* Gradio

### Installation & Usage
1. Clone the repository:
   ```bash
   git clone [https://github.com/negilbabu/multimodal-chatbot-plantguard.git](https://github.com/negilbabu/multimodal-chatbot-plantguard.git)
