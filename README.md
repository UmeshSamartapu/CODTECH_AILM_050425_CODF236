# 🧠 CODTECH Internship Project Portfolio

- **Intern Name:** Samartapu Umesh
- **Intern ID:** C0DF236
- **Organization:** CODTECH IT SOLUTIONS PVT. LTD.
- **Internship Period:** April 20th, 2025 – May 20th, 2025

# 📋 Overview
This repository contains the completed project assignments for the 4-week AI Internship at CODTECH IT SOLUTIONS. Each project demonstrates the practical application of machine learning and deep learning techniques using modern Python libraries, APIs, and frameworks.

# ✅ Completed Projects

# 🔹 [CODTECH 01] Text Summarization Tool
## Description:
A web-based application that provides AI-powered abstractive text summarization using the BART-large-CNN model.

## 🔧 Tech Stack:
```bash
FastAPI,
Uvicorn, 
Transformers, 
NLTK, 
Textwrap, 
HTML/CSS/JS
```

## 🌟 Features:

- Web and API interfaces
- Adjustable summary length
- Real-time performance tracking
- Responsive UI

## 📁 Folder Structure:
```bash
text_summarizer_app/
├── app/
│   ├── main.py, schemas.py, services/
│   └── static/ (style.css, script.js)
├── templates/ (index.html)
├── requirements.txt
├── run.py
└── README.md
```

## 🚀 Run Locally:
```bash
git clone https://github.com/UmeshSamartapu/text_summarizer_app.git
cd text_summarizer_app
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
pip install -r requirements.txt
python -c "import nltk; nltk.download('punkt')"
python run.py
Open in browser: http://localhost:8000
```

# 🔹 [CODTECH 02] Speech Recognition System
## Description:
A complete speech-to-text system with CLI and web-based interfaces using:
- Google Web Speech API
- Facebook Wav2Vec2 model

## 🔧 Tech Stack:
```bash
FastAPI,
SpeechRecognition,
Transformers,
PyDub,
Librosa,
Torch
```

## 📁 Folder Structure:
```bash
speech-recognition-system/
├── main.py, api.py
├── audio_processing.py
├── wav2vec2_recognition.py, google_speech_recognition.py
├── static/, templates/, uploads/, outputs/
└── requirements.txt
```

## 🌐 Usage:
```bash
uvicorn api:app --reload
Open in browser: http://localhost:8000
```

## 📊 Comparison Table:

- Method	Accuracy	Internet	Speed
- Google API	Medium	Yes	Fast
- Wav2Vec2	High	No	Slow

# 🔹 [CODTECH 03] Neural Style Transfer 🎨
## Description:
Transfers the artistic style of one image to another using a pre-trained VGG19 model. Available as both a Jupyter Notebook and a Web App.

## 🔧 Tech Stack:
```bash
PyTorch, Pillow, ImageIO, FastAPI, HTML/CSS
```

## 📁 Folder Structure:
```bash
Neural_Style_Transfer/
├── Neural Style Transfer.ipynb
├── content_image/, style_image/, output/
Web_Application/
├── app.py, style_transfer.py, nst_utils.py
├── templates/, static/, uploads/
└── requirements.txt
```

## 🖼 Features:

- Live style transfer via web app
- Saves styled images and optimization GIF
- Adjustable weights for fine-tuning results

## 🚀 Web App:
```bash
cd Neural_Style_Transfer/Web_Application
pip install -r requirements.txt
python app.py
Access: http://127.0.0.1:5000/
```

# 🔹 [CODTECH 04] Generative Text Model
## Description:
Generates creative and contextually relevant text from a given prompt using Hugging Face's GPT-2.

## 🔧 Tech Stack:
```bash
Transformers,
Torch,
FastAPI,
HTML/CSS
```

## 📁 Folder Structure:
```bash
generative_text_model/
├── app.py
├── generate.py
├── templates/index.html
├── static/style.css
└── requirements.txt
```

## 🌟 Features:

- Real-time text generation from prompts
- Web-based interactive interface
- Uses pretrained GPT-2 model

## 🚀 Usage:
```bash
pip install -r requirements.txt
python app.py
Open in browser: http://localhost:5000
```

## 📜 License
This project is open-source and available under the MIT License.

## 🙌 Acknowledgements
Special thanks to CODTECH IT SOLUTIONS PVT. LTD. for the opportunity and guidance during this internship.

## Contact:
🧑‍💼 Neela Santhosh Kumar

📩 Hr@codtechitsolutions.com

📞 +91 9848925128

🌐 www.codtechitsolutions.com

## 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/umeshsamartapu/)
[![Twitter](https://img.shields.io/badge/-Twitter-1DA1F2?style=flat-square&logo=twitter&logoColor=white)](https://x.com/umeshsamartapu)
[![Email](https://img.shields.io/badge/-Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:umeshsamartapu@gmail.com)
[![Instagram](https://img.shields.io/badge/-Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/umeshsamartapu/)
[![Buy Me a Coffee](https://img.shields.io/badge/-Buy%20Me%20a%20Coffee-FBAD19?style=flat-square&logo=buymeacoffee&logoColor=black)](https://www.buymeacoffee.com/umeshsamartapu)

---

🔥 Always exploring new technologies and solving real-world problems with code!
