---
sdk: streamlit
app_port: 8501
---

# 🌿 EmotiBot

[![Streamlit](https://img.shields.io/badge/Streamlit-Ready-green)](https://streamlit.io)  
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-🚀-orange)](https://huggingface.co/)  
[![Python](https://img.shields.io/badge/Python-3.10-blue)](https://python.org)  
[![License: MIT](https://img.shields.io/badge/License-MIT-lightgrey)](/LICENSE)

A friendly, multi‐turn chatbot built with Streamlit and Hugging Face’s emotion‐detection pipeline. EmotiBot listens to how you feel and offers empathetic, context‐aware responses.

---

## 📖 Table of Contents

1. [🚀 Live Demo](#-live-demo)  
2. [🧩 Features](#-features)  
3. [🗂️ Project Structure](#️-project-structure)  
4. [⚙️ Installation](#️-installation)  
5. [▶️ Usage](#️-usage)  
6. [🔧 Customization](#-customization)  
7. [🤝 Contributing](#-contributing)  
8. [📜 License](#-license)

---

## 🚀 Live Demo

👉 https://huggingface.co/spaces/Opinder29/emotibot_v2

---

## 🧩 Features

- **Emotion Detection**  
  Uses `j-hartmann/emotion-english-distilroberta-base` to classify text into:  
  `sadness`, `anger`, `love`, `joy`, `fear`, `surprise`, `disgust`, `neutral`.

- **Empathetic Replies**  
  Pre-written, supportive responses for each emotion.

- **Multi‐Turn Chat**  
  Maintains conversation history in the browser session.

- **Spelling Correction**  
  Auto-corrects typos with TextBlob for smoother conversations.

---

## 🗂️ Project Structure

```text
My_projects/
├── app.py               # Main Streamlit chatbot
├── requirements.txt     # Project dependencies
├── README.md            # This document
└── .cache/              # Auto-generated model cache
