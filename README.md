# 🧠 Research Buddy - Your Smart Research Assistant

**Research Buddy** is a productivity-boosting Chrome Extension designed to assist researchers, students, and curious minds. It uses **Google Gemini AI API** to summarize web content and selected text, helping users quickly grasp key ideas. You can also save important notes for future reference.

---

## 🚀 Features

- ✨ **AI-Powered Summarization**: Get quick summaries of web pages or selected text using Google Gemini.
- 🖱️ **Context Menu Support**: Right-click to summarize selected text on any webpage.
- 💾 **Note Saving**: Save personalized notes and summaries for later use.
- 📚 **Clean & Simple UI**: Minimalistic and intuitive interface for distraction-free research.

---

## 🛠️ Tech Stack

| Technology      | Usage                       |
|-----------------|-----------------------------|
| HTML/CSS/JS     | Core frontend development   |
| Chrome API      | Extension integration       |
| Gemini AI API   | Summarization functionality |
| LocalStorage    | Storing user notes          |

---

## 📸 Screenshots

### 🔍 Summarize Tab Content
![Summarize Tab](./screenshots/summarize-tab.png)

### 📄 Summarize Selected Text
![Summarize Selection](./screenshots/summarize-selection.png)

### 📝 Saved Notes
![Saved Notes](./screenshots/saved-notes.png)

> 📝 Make sure you have these images in a folder named `screenshots` inside your project root.

---

## 🧪 How to Use

1. Clone or download this repository.
2. Go to `chrome://extensions/` in your browser.
3. Enable **Developer Mode** (top-right).
4. Click **Load unpacked** and select the project folder.
5. Start using **Research Buddy** directly from your browser toolbar!

---

## 📁 Project Structure

<pre> research-buddy/ │ ├── backend/ │ ├── .mvn/wrapper/ │ ├── src/ │ ├── .gitattributes │ ├── .gitignore │ ├── mvnw │ ├── mvnw.cmd │ └── pom.xml │ ├── frontend/ │ ├── background.js │ ├── manifest.json │ ├── sidepanel.css │ ├── sidepanel.html │ ├── sidepanel.js │ └── research-assistant.png </pre>


---

## 🔐 Gemini API Setup

- Create a `.env` file or directly add your **Gemini API Key** in `popup.js` (not recommended for production).
- Use `fetch()` to call the Gemini model with your content.
- Handle and display the summary.

---

## 👩‍💻 Author

**Sakshi Singh**  
Generative AI Enthusiast | Software Developer  
[LinkedIn Profile](https://www.linkedin.com/in/sakshi-amit-singh/)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

- Google Gemini AI
- Chrome Extensions API
