# AI Image Caption Generator 🤖🖼️

An AI-powered image caption generator that analyzes uploaded images and creates **short, professional, and creative captions** using Gemini AI. It can also generate relevant social media hashtags automatically.

## 🚀 Features

* 🖼️ Upload and analyze images
* ✍️ Generate AI-powered captions
* 🎯 Choose from different caption styles:

  * Short
  * Professional
  * Creative
* #️⃣ Generate relevant hashtags
* 🖥️ Simple interactive interface using IPyWidgets
* ⚡ Runs easily in Google Colab

## 🛠️ Technologies Used

* Python
* Google Colab
* Gemini AI
* Google GenAI SDK
* PIL (Pillow)
* IPyWidgets

## 🔄 How It Works

```text
Upload Image
     ↓
AI Image Analysis
     ↓
Select Caption Style
     ↓
Gemini AI Generates Caption
     ↓
Generate Relevant Hashtags
     ↓
Display Final Result
```

## 📋 Caption Styles

### Short

Generates a simple and concise caption.

### Professional

Generates a polished caption suitable for professional platforms.

### Creative

Generates an engaging and creative social media caption.

## ⚙️ Installation

Install the required libraries in Google Colab:

```python
!pip install -q google-genai pillow
```

## 🔑 API Key Setup

The project uses a Gemini API key. For security, the API key is entered securely using `getpass` instead of being written directly in the notebook.

```python
import getpass
from google import genai

api_key = getpass.getpass("Enter your Gemini API Key: ")
client = genai.Client(api_key=api_key)
```

**Important:** Never upload or publish your actual API key on GitHub.

## ▶️ How to Run

1. Open the notebook in Google Colab.
2. Install the required libraries.
3. Enter your Gemini API key securely.
4. Upload an image.
5. Select a caption style.
6. Click **Generate Caption**.
7. View the generated caption and hashtags.

## 📌 Example Output

```text
Caption Style: Professional

Generated Caption:
A beautiful moment captured with simplicity and elegance.

Hashtags:
#Photography #AI #ImageCaption #CreativeAI #GenerativeAI
```

## 🌟 Future Improvements

* Add multiple language support
* Add automatic image category detection
* Add Instagram and LinkedIn caption modes
* Create a Streamlit web application
* Add downloadable caption reports

## 👩‍💻 Author

**Laiba Yaseen**

This project was developed as a practical Generative AI project using Python, Google Colab, and Gemini AI.
