# PotatoCare AI 🥔🌿

PotatoCare AI is a Streamlit-based deep learning application for potato leaf disease classification using an EfficientNet model.
It predicts one of:
- Early Blight
- Late Blight
- Healthy

## Project Structure

```
PotatoCare-AI/
├── models/
│   └── potato_model.keras
├── venv/              # ignored by git
├── .gitignore
├── Home.py
└── requirements.txt
```

## Setup (Windows)

```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
```

## Run the App

```bash
streamlit run Home.py
```

## Author
Anjalika Wijesiri
