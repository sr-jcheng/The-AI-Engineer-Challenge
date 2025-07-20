# 🤖 AI Chat Interface Frontend

Welcome to your beautiful AI chat interface! This is a sleek, modern frontend that connects to your FastAPI backend.

## ✨ Features

- **Beautiful UI**: Modern gradient design with smooth animations
- **Real-time streaming**: Watch AI responses appear as they're generated
- **Responsive design**: Works great on desktop and mobile
- **Error handling**: Clear error messages when something goes wrong
- **Keyboard shortcuts**: Press Enter to send messages

## 🚀 How to Run

1. **Start your FastAPI backend** (in the `api` directory):
   ```bash
   cd ../api
   python app.py
   ```

2. **Open the frontend** in your browser:
   - Simply double-click `index.html` or
   - Open it in your browser: `file:///path/to/frontend/index.html`

## 🎯 How to Use

1. **Enter your OpenAI API key** in the password field
2. **Optionally add a developer message** to set the AI's behavior
3. **Type your message** and press Enter or click Send
4. **Watch the magic happen** as the AI responds in real-time!

## 🔧 Configuration

The frontend connects to `http://localhost:8000` by default. If your backend runs on a different port, update the `API_BASE_URL` in the JavaScript code.

## 🎨 Customization

Feel free to modify the CSS styles to match your brand colors or preferences. The design is fully responsive and mobile-friendly!

---

**Pro tip**: Keep your API key secure and never share it publicly! 🔐 