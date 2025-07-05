
# 🌐 Multi-Language Multi-Modal Chatbot

An interactive AI-powered chatbot that supports:
✅ Multi-language text chat  
✅ Image understanding (describe an uploaded image)  
✅ Image generation (using Stable Diffusion)  

Built using **Google Gemini**, **Stable Diffusion**, **Streamlit**, and deployed via **ngrok**.

---

## 🚀 Features

- 🤖 **Text Chat (Multi-Language):**  
  Converse with the chatbot in English, Spanish, French, Tamil, or German.  
  Detects your input language and responds appropriately & culturally.

- 🖼️ **Image Understanding:**  
  Upload an image, and the bot will analyze and describe its contents.

- 🎨 **Image Generation:**  
  Provide a creative text prompt, and the bot generates an image using Stable Diffusion.

---

## 🧰 Tech Stack

- [Google Gemini API](https://ai.google) — For text and vision capabilities
- [Stable Diffusion](https://huggingface.co/CompVis/stable-diffusion-v1-4) — Image generation
- [Streamlit](https://streamlit.io) — Web UI
- [ngrok](https://ngrok.com) — Public URL for Streamlit app
- [langdetect](https://pypi.org/project/langdetect/) — Detect input language

---

## 🔧 Setup & Run

### 📋 Prerequisites
- Python ≥ 3.8
- Google Gemini API key
- HuggingFace token (for Stable Diffusion)
- ngrok authtoken

### 📥 Install dependencies
Run the following commands to set up:

```bash
pip install -r requirements.txt
```

Or manually:
```bash
pip install torch==2.6.0 torchvision==0.21.0 torchaudio==2.6.0
pip install diffusers transformers accelerate google-generativeai pillow streamlit pyngrok langdetect
pip install google-generativeai==0.8.5 google-ai-generativelanguage==0.6.15
```

---

### 🔑 Configure your keys
You will be prompted in the terminal to enter:
- **Google Gemini API Key**
- **HuggingFace Token**
- **ngrok authtoken**

These are set as environment variables automatically.

---

### ▶️ Run the app
```bash
python app.py
```

Wait for the public URL printed by ngrok, and open it in your browser!

---

## 📄 File Structure

```
├── app.py              # Main Streamlit app
├── requirements.txt    # Python dependencies
├── README.md           # This file
```

---

## 🙏 Acknowledgments

- [Google AI](https://ai.google) for Gemini API
- [Hugging Face](https://huggingface.co/) for Stable Diffusion
- [Streamlit](https://streamlit.io) for the awesome UI

---

## 📜 License

MIT License.  
Feel free to use, modify, and share.
