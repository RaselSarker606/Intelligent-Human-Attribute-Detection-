## 🤖 Human Attribute Recognition with AI

A Streamlit-based web application that utilizes Google Gemini AI to analyze human attributes from images. This project leverages advanced AI capabilities to provide insights into various facial attributes.

---

## 📖 Overview

This project enables users to:

- Upload an image for analysis
- Receive detailed predictions about human attributes
- Use AI-powered recognition to estimate gender, age, emotions, and more

It is designed for applications in AI-assisted identity analysis and facial attribute recognition.

---

## 📂 Features

- 📸 **Image Upload Support**: Users can upload \`.png\`, \`.jpg\`, or \`.jpeg\` images.
- 🤖 **AI-Powered Analysis**: Uses Google Gemini AI for attribute detection.
- 📊 **Detailed Human Attribute Extraction**:
  - Gender
  - Age Estimate
  - Ethnicity
  - Mood & Emotions
  - Facial Expression
  - Glasses & Headwear
  - Hair & Eye Color
  - Confidence Score for Predictions
- 🖼️ **Interactive UI**: Streamlit-powered web app for seamless user experience.

---

## 🛠️ Methodology

### 🔍 AI Model
- Uses \`google.generativeai\` to load the \`Gemini-1.5-flash-latest\` model.
- AI is prompted to analyze facial attributes with structured output.

### 🏗️ Implementation
1. **Image Upload**: Users upload an image using \`st.file_uploader\`.
2. **AI Processing**:
   - The AI receives the image along with a structured prompt.
   - It returns key facial attributes and confidence scores.
3. **Results Display**:
   - Image and analysis results are displayed side by side in two columns.

---

## 🚀 Installation & Usage

### 📦 Requirements

- Python 3.x
- Streamlit
- Google Generative AI (\`google-generativeai\`)
- PIL (Pillow)

### 🔧 Setup



### ▶️ Running the Application



## 📌 Future Improvements

- 🎭 **Face Landmark Detection**: Identify specific facial landmarks.
- 🌍 **Multilingual Support**: Add support for multiple languages.
- 📊 **Confidence Visualization**: Graphically represent AI prediction confidence.
- 🔍 **More Attributes**: Extend detection to accessories, background details, etc.

---

🚀 **Stay tuned for updates!**`;

