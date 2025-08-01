# NERsume: An NLP Resume Parser using Named Entity Recognition

NERsume is an AI-powered resume parser built with Natural Language Processing (NLP). It extracts structured information such as **Name**, **Skills**, **Degree**, **Institutions**, and **Work Experience** from resumes in `.pdf` or `.txt` formats using **SpaCy’s Named Entity Recognition (NER)**.

> ✨ Ideal for HR automation, recruiting systems, or applicant tracking tools.

---

##  Demo

You can run the app using:
- 🔗 **Google Colab** (with Gradio or Streamlit support)
- 💻 Local machine using Python & Streamlit

---

## Features

- ✅ Extracts:
  - Name
  - Degree
  - Work Experience
  - Institutions
  - Skills (optional via keywords)
- 🧾 Accepts `.pdf` and `.txt` resumes
- 📤 Outputs JSON format
- 🖥️ Web UI with **Gradio** or **Streamlit**
- 🔁 Works offline or in Colab (with ngrok)

---

## Tech Stack

- **Python**
- **SpaCy (NER)**
- **PyMuPDF (fitz)** for PDF reading
- **Gradio / Streamlit** for UI
- **Google Colab** for cloud-based execution

---

## Folder Structure

```bash
NERsume/
├── app.py              # Streamlit app
├── resume_parser.py    # Core logic for entity extraction
├── utils.py            # PDF and TXT reading helpers
├── requirements.txt
├── sample_resumes/     # Upload your test resumes here
├── outputs/            # Parsed resume JSON results
└── README.md
```
## Output :
<img width="1859" height="958" alt="image" src="https://github.com/user-attachments/assets/00bec147-3a3a-425f-b9e9-d77e3a448a68" />
<img width="1896" height="972" alt="image" src="https://github.com/user-attachments/assets/9f226ad4-6eb1-4b28-a353-336161eaa732" />

