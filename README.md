# 📧 Auto Email Responder with SMTP Send (Streamlit Secure)

An agentic AI app that generates and sends smart email replies using GPT-4 and SMTP integration.

---

## 🚀 Features
- Paste received email
- Choose tone (Professional, Friendly, Apologetic, Persuasive)
- Enter recipient email
- Generates a GPT-4-based reply and sends it via SMTP

---

## ✅ Secure Streamlit Secrets Setup

### Add this in your Streamlit Cloud Secrets:

```
OPENAI_API_KEY = "sk-xxxxxxxxxxxxxxxxxxxxx"
SENDER_EMAIL = "your-email@gmail.com"
EMAIL_PASSWORD = "your-app-password"
SMTP_SERVER = "smtp.gmail.com"
SMTP_PORT = 587
```

> 🔐 Note: Use Gmail App Password if you have 2FA enabled.

---

## 🛠 Deployment Instructions

1. Push this folder to GitHub
2. Deploy on [https://streamlit.io/cloud](https://streamlit.io/cloud)
3. Add your OpenAI and Email credentials in **Secrets Manager**
4. You're live and can send emails autonomously!

---

## 📁 Project Structure
```
auto_email_agent_smtp/
├── main.py
├── agents/
│   └── email_agent.py
├── utils/
│   └── email_sender.py
├── .streamlit/
│   └── config.toml
├── requirements.txt
└── README.md
```