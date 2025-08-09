# 🌐 Translator Agent

A simple yet powerful translator app built with **Streamlit** and powered by **Google Gemini API**.  
It can automatically detect the source language and translate it into your desired target language, while keeping the meaning, tone, and context accurate.

---

## 🚀 Features
- **Automatic Language Detection** – No need to specify the source language.
- **Multi-language Support** – Translate any language into Urdu or English.
- **Custom Creator Response** – Answers questions like *"Who made you?"* with a fixed response.
- **Clean & Minimal UI** – Easy to use with a simple text box and translate button.

---

## 📦 Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/MehwishRazzak786/translator-agent.git
cd translator-agent

2️⃣ Create a virtual environment
Using uv:

uv venv
source .venv/bin/activate  # On macOS/Linux
.venv\Scripts\activate     # On Windows

Or using venv:

python -m venv .venv
source .venv/bin/activate  # On macOS/Linux
.venv\Scripts\activate     # On Windows

3️⃣ Install dependencies
If you are using pyproject.toml:

pip install .

Or if you prefer using requirements.txt:

pip install -r requirements.txt

🔑 Environment Variables
Create a .env file in the project root and add:

GEMINI_API_KEY=your_api_key_here

▶️ Run the app

streamlit run main.py

📂 Project Structure

translator-agent/
│── main.py               # Streamlit app entry point
│── pyproject.toml        # Project dependencies & metadata
│── README.md             # Project documentation
│── .gitignore            # Ignored files & folders
│── .env                  # Environment variables (not committed)


👩‍💻 Creator
Mehwish Razzak
"It was created by Mehwish Razzak."


