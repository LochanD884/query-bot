# Query Bot
Query Bot is a simple, elegant AI-powered chatbot built with Flask. It uses Google’s Gemini (or your preferred LLM) to answer user queries in real time. The bot displays both a rendered and Markdown version of the response, while maintaining a chat history for a smooth conversational experience.

## 🚀 Features
✅ AI-powered query answering

✅ Supports Markdown rendering

✅ Remembers chat history in session

✅ Fully built with Flask (no Gradio)

✅ Clean and modern HTML UI with Bootstrap

✅ Easy to customize and extend

## ⚙️ Requirements
Python 3.8+

Flask

google-generativeai (for Gemini)

markdown

## 🧩 Installation
### 1️⃣ Clone this repo

````
git clone https://github.com/yourusername/query-bot.git

cd query-bot
````

### 2️⃣ Create a virtual environment (optional but recommended)

```
python -m venv venv

source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3️⃣ Install dependencies

```
pip install -r requirements.txt
```

### 4️⃣ Add your Gemini API key

In app.py, replace:

``` genai.configure(api_key="YOUR_GEMINI_API_KEY")```

with your actual key, or set it as an environment variable.

## 🚦 Running the Bot

python app.py

```Visit http://127.0.0.1:5000 in your browser.```

## 📝 Customization
Change the prompt styling in app.py

Tweak the front-end in templates/index.html

Add CSS/JS to static/ if you want fancy effects

## 🤝 Contributing
Pull requests are welcome!
If you find a bug or want a feature, open an issue first.
