# 💼 Resume Parser with Streamlit UI

A smart **Resume Parser** that extracts structured data such as **name, email, phone number, skills, education, experience**, and more from resumes using **Natural Language Processing (NLP)** and displays the results through an interactive **Streamlit web interface**.

This tool helps HR teams, recruiters, and developers automate resume screening and convert unstructured `.pdf` and `.docx` resumes into clean, structured data.

---

## 🚀 Live Demo (Streamlit Cloud)

👉 **Try it instantly on Streamlit Cloud:**
[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://streamlit.io/)

> _Note: Replace the above link with your actual deployed app URL._

---

## 🧠 Key Features

- ✅ Upload resumes in **.pdf** or **.docx** format
- 🧾 Automatically extract:
  - Name
  - Email
  - Phone number
  - Skills
  - Education
  - Experience
- 📋 Clean, structured output in the UI
- 🔍 Built using NLP (spaCy) and regex
- 🖥️ Streamlit-based interactive frontend
- 🌐 Supports both **local** and **cloud** deployment

---

## 🛠️ Technologies Used

| Layer       | Tech Stack             |
|-------------|------------------------|
| Frontend    | Streamlit              |
| Backend     | Python                 |
| NLP Engine  | spaCy (`en_core_web_sm`) |
| File Parsers| PyPDF2, python-docx    |
| Resume Types| `.pdf`, `.docx`        |

---

## 📁 Project Structure

```
ResumeParser/
├── parser.py             # Core logic for extracting resume data
├── app.py                # Streamlit frontend
├── requirements.txt      # List of dependencies
└── README.md             # Project documentation
```

---

## 💻 How to Run Locally (VS Code or Terminal)

### 1. Clone the Repository

```bash
git clone https://github.com/YourUsername/ResumeParser.git
cd ResumeParser
```

### 2. Install Required Libraries

```bash
pip install -r requirements.txt
python -m spacy download en_core_web_sm
```

### 3. Run the Streamlit App

```bash
streamlit run app.py
```

> A browser tab will open where you can upload a resume and see extracted results.

---

## ☁️ How to Deploy on Streamlit Cloud

1. Push your code to a **public GitHub repository**
2. Go to [Streamlit Cloud](https://streamlit.io/cloud)
3. Click **"New app"**
4. Select your GitHub repo and branch
5. Set `app.py` as the main file
6. Add `requirements.txt`
7. Click **Deploy**

Done! Your Resume Parser is now online.

---

## 📷 Screenshot


![image](https://github.com/user-attachments/assets/4ec1cad2-516b-4b55-9f80-6fa620b5d546)

---

## ✨ Future Improvements

- ⬇️ Allow downloading parsed data (JSON/CSV)
- 🤖 Advanced NLP for education & experience parsing
- 📑 Batch processing of multiple resumes
- 🧠 ML model for skill inference
- 📊 Add dashboard or analytics

---

## 🙏 Acknowledgments

- [`spaCy`](https://spacy.io/)
- [`Streamlit`](https://streamlit.io/)
- [`PyPDF2`](https://pypi.org/project/PyPDF2/)
- [`python-docx`](https://python-docx.readthedocs.io/en/latest/)

---

## 📜 License

This project is licensed under the MIT License.
