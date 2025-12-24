

# 🌐 PolyGlot AI

**PolyGlot AI** is a lightweight, mobile-responsive web application that bridges language barriers with real-time translation and voice synthesis. Built with vanilla web technologies, it offers a seamless experience for translating text and speech across multiple languages.

## ✨ Features

* **Real-time Translation:** Instantly translate text between English, Hindi, Marathi, Spanish, French, German, and Japanese.
* **🗣️ Text-to-Speech (TTS):** Listen to translations with adjustable speed controls using the native Web Speech API.
* **🎙️ Voice Input:** Speech-to-text support for hands-free typing (Supported on Chrome & Android).
* **🌗 Dark/Light Mode:** Dynamic theme toggling for comfortable viewing in any lighting condition.
* **📜 History & Storage:** Automatically saves your recent translations to Local Storage so you never lose track.
* **📱 Mobile First:** Fully responsive design with touch-friendly controls and native sharing capabilities.

## 🚀 Tech Stack

* **Frontend:** HTML5, CSS3 (Custom Variables & Flexbox), Vanilla JavaScript.
* **APIs:** * [MyMemory Translation API](https://mymemory.translated.net/) (No API key required for basic usage).
    * Web Speech API (Synthesis & Recognition).

## 🛠️ Installation & Usage

Since this is a client-side application, no server installation is required!

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/polyglot-ai.git](https://github.com/your-username/polyglot-ai.git)
    ```
2.  **Navigate to the project folder:**
    ```bash
    cd polyglot-ai
    ```
3.  **Run the app:**
    * Simply open `index.html` in your web browser.
    * *Note:* For the microphone feature to work optimally, it is recommended to run this on a local server (e.g., VS Code Live Server) or via HTTPS, as browsers often block microphone access on purely local `file://` paths.

## 📖 Browser Compatibility

| Feature | Chrome / Edge | Firefox | Safari (iOS/Mac) |
| :--- | :---: | :---: | :---: |
| **Translation** | ✅ | ✅ | ✅ |
| **Text-to-Speech** | ✅ | ✅ | ✅ |
| **Voice Input** | ✅ | ❌ | ❌ (Limited support) |

*> Note: The Voice Input feature utilizes `webkitSpeechRecognition`, which is currently best supported on Chromium-based browsers (Chrome, Edge, Brave, Android Webview).*

## 🎨 Customization

You can easily add more languages by editing the `<select>` options in `index.html`:

```html
<option value="it-IT">🇮🇹 Italian</option>
