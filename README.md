
# 🩺 Medical Assistant Chatbot

An AI-powered Medical Assistant Chatbot built using **Python, Streamlit, Ollama, and Llama 3.2**.

This chatbot provides general medical information and healthcare education through an interactive conversational interface. It is designed to answer medical and health-related questions while rejecting unrelated topics.

---

## 📌 Project Overview

The Medical Assistant Chatbot is an AI-based application that helps users understand general healthcare information.

Powered by Meta's Llama 3.2 model through Ollama, the application provides educational information about diseases, symptoms, medications, nutrition, medical terminology, and preventive healthcare.

The application also includes a medical topic classification system that helps restrict conversations to healthcare-related topics.

---

## ✨ Features

- 🩺 **Medical Information:** Provides general medical and healthcare information.
- 🦠 **Disease Education:** Explains common diseases and medical conditions.
- 💊 **Medication Information:** Provides general information about medicines and drug safety.
- 🥗 **Nutrition Guidance:** Explains nutrition and its relationship with health.
- 🧬 **Medical Terminology:** Explains medical terms in simple language.
- 🧪 **Medical Reports:** Helps users understand common medical tests and reports.
- 🧠 **Mental Health Education:** Provides general mental health information.
- ❤️ **Preventive Healthcare:** Shares general health and hygiene guidance.
- 🔍 **Medical Topic Classification:** Identifies unrelated questions and politely rejects them.
- 💬 **Interactive Chat Interface:** Supports conversational interaction.
- ⚡ **Streaming Responses:** Displays AI-generated responses in real time.
- 🌙 **Dark Mode UI:** Provides a modern dark-themed interface.
- 🗑️ **Clear Chat:** Allows users to reset conversation history.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Streamlit | Web application interface |
| Ollama | Local AI model execution |
| Llama 3.2 | Large language model |
| HTML/CSS | Interface styling |

---

## 📂 Project Structure

```text
MedicalAssistant/
│
├── app.py
│
├── .streamlit/
│   └── config.toml
│
├── README.md
│
└── requirements.txt
```

---

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/MedicalAssistant.git
```

Navigate to the project directory:

```bash
cd MedicalAssistant
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the environment.

**Windows:**

```bash
venv\Scripts\activate
```

**Linux / macOS:**

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Install Ollama

Download and install Ollama:

https://ollama.com/download

### 5. Download Llama 3.2

Open your terminal and execute:

```bash
ollama pull llama3.2
```

Make sure Ollama is running before starting the application.

### 6. Run the Application

```bash
streamlit run app.py
```

The application will open in your browser, usually at:

```text
http://localhost:8501
```

---

## 📦 Requirements

Create a `requirements.txt` file containing:

```text
streamlit
ollama
```

---

## 🎨 Dark Mode Configuration

The application uses a custom dark interface.

Create the following configuration file:

`.streamlit/config.toml`

Add:

```toml
[theme]
base = "dark"
primaryColor = "#20B2AA"
backgroundColor = "#0E1117"
secondaryBackgroundColor = "#161D27"
textColor = "#F1F5F9"
font = "sans serif"
```

---

## 💡 Example Questions

Users can ask questions such as:

- What is diabetes?
- What are the symptoms of anemia?
- What causes high blood pressure?
- What is vitamin D deficiency?
- What are the health benefits of drinking water?
- What is the difference between viruses and bacteria?
- What is the importance of preventive healthcare?

### Medical Topic Restriction

The chatbot is designed specifically for healthcare-related conversations.

For example:

| Question | Expected Result |
|---|---|
| What is diabetes? | Medical information |
| What causes fever? | Medical information |
| What are the benefits of vitamin D? | Health information |
| Give me a coffee recipe. | Out-of-scope response |
| Tell me a joke. | Out-of-scope response |
| Write Python code. | Out-of-scope response |

---

## 🔒 Medical Safety Disclaimer

**Important:**

This chatbot is developed for educational and informational purposes only.

- It does not provide medical diagnoses.
- It does not replace qualified healthcare professionals.
- It does not prescribe personalized medication dosages.
- Users should consult qualified healthcare professionals for medical advice.
- For potentially life-threatening emergencies, seek immediate emergency medical assistance.

AI-generated medical information may be inaccurate or incomplete. Always verify important medical information with reliable healthcare professionals.

---

## 🚀 Future Improvements

Potential future enhancements include:

- Medical PDF report analysis.
- Medical FAQ database integration.
- User authentication.
- Persistent conversation history.
- Multilingual medical assistance.
- Voice-based interaction.
- Improved medical question classification.
- Integration with trusted medical knowledge sources.

---

## 👨‍💻 Author

**Your Name**

GitHub: https://github.com/YOUR-USERNAME

---

## 📄 License

This project is available for educational and learning purposes.

You may add an MIT License if you want to distribute the project under that license.

---

⭐ If you find this project useful, consider giving the repository a star!
