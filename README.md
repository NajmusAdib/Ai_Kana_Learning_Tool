# 🎌 Interactive Japanese Kana Learning Chart

A lightweight, responsive web app for learning Japanese Kana (Hiragana & Katakana) through interactive charts, pronunciation tips, AI-generated examples, and handwriting practice.

## ✨ Features

- **Clickable Kana Chart** (Hiragana & Katakana)
- **Dakuten & Handakuten Toggle**
- **Romaji Display** for all characters
- **Speech Synthesis** using your browser’s Japanese voice
- **AI Features (Gemini):**
  - Generate pronunciation tips for each character
  - Show example words and sentences
  - Provide etymology/history of selected Kana
  - Offer general pronunciation advice
- **Handwriting Practice Canvas**
  - Draw Kana with mouse/touch
  - See reference shadow
  - AI-powered handwriting feedback

## 🖥️ Live Demo

> Just open `AiKanaLearning.html` in any modern web browser. No installation or dependencies needed.

## 📁 Project Structure

- `AiKanaLearning.html` – All-in-one HTML file (HTML, CSS, JS)
- Built-in Gemini API integration (You must provide your own API key)

## 🔧 Requirements

- Modern browser (Chrome, Firefox, Edge, etc.)
- Internet connection (for Gemini AI features)
- Browser must support `speechSynthesis` API for audio playback

## ⚙️ Setup & Usage

1. Clone or download this repo.
2. Open `AiKanaLearning.html` in a browser.
3. Click on any character to:
   - Hear its pronunciation
   - View its Romaji
   - Practice writing
   - Generate AI-powered examples and tips

## 🧠 AI Integration

This project uses [Google Gemini](https://ai.google) for:
- Pronunciation advice
- Word and sentence generation
- Historical insights
- Handwriting feedback

## 🔑 How to Get a Gemini API Key

To enable AI features, you need your own Gemini API key.

### Steps:
1. Visit the [Google AI Studio](https://aistudio.google.com/app/apikey).
2. Sign in with your Google account.
3. Click **"Create API key"**.
4. Copy the key provided.
5. Open `AiKanaLearning.html` in a text/code editor.
6. Find the line:
   ```js
   const API_KEY = "your-key-here";

> Replace the placeholder `API_KEY` in the script with your own Gemini API key to enable AI features.

## ✍️ Handwriting Practice

- Draw the selected Kana character
- Get real-time AI feedback on accuracy
- Works with mouse and touchscreen

## 🗣️ Voice Support

Speech is generated using your browser’s built-in Japanese voice. Make sure:
- You're using a browser with Japanese voice support
- The voice is selected automatically on load

## 📦 Exporting/Embedding

You can embed this chart in any educational site by:
- Copying the `AiKanaLearning.html` content into an iframe
- Hosting it on your preferred platform

## 📄 License

MIT License – Free to use, modify, and share.

## 🙏 Credits
1. Md. Najmos Salahin

Created with ❤️ for learners of Japanese. Powered by:
- HTML5, CSS3, JavaScript
- Google Gemini AI
- Web Speech API
