# First Internship Task – Google Colab AI & Gemini API

## 📌 Project Overview
This project demonstrates how to use **Google Colab** to interact with Large Language Models (LLMs) via the `google-colab-ai` Python library and **Gemini API** by Google DeepMind.  
It is designed as a beginner-friendly introduction to AI model usage without the need for an API key (for Colab Pro users), and also shows how to connect with the Gemini API for more advanced capabilities.

## 🚀 Features
- Access popular LLMs in Google Colab without an API key.
- Send text prompts and get AI-generated responses.
- Explore Google DeepMind's **Gemini models** (multimodal: text, images, code, audio).
- Learn how to obtain and use a Gemini API key.

## 📂 Project Structure
- **Colab Setup**: Installing and importing `google-colab-ai`.
- **Basic LLM Query**: Sending prompts and displaying responses.
- **Gemini API**: Connecting with API key and running prompts.
- **Example Outputs**: Sample responses from the models.

## 🛠️ Requirements
- Google Colab account (Pro users can use LLMs without API key).
- Python 3.x
- Internet connection

## 📖 How to Use
1. Open the `.ipynb` file in Google Colab.
2. For API-free usage:
   ```python
   from google.colab import ai
   response = ai.generate_text("Your question here")
   print(response)
