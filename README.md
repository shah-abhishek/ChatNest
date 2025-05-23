# 🪺 ChatNest

**ChatNest** is a lightweight, real-time chat application that allows multiple users to communicate instantly in a shared chat room. Built with a FastAPI backend and a simple HTML/JavaScript frontend, it leverages WebSockets for seamless live communication.

---

## 🚀 Features

- 🔄 Real-time messaging using WebSockets
- 🧑‍🤝‍🧑 Multi-user chat support
- 🖥️ Clean and minimal frontend built with plain HTML, CSS, and JS
- ⚡ FastAPI backend for performance and simplicity
- 🕒 Timestamps for each message

---

## 🛠️ Tech Stack

- **Backend:** [FastAPI](https://fastapi.tiangolo.com/)
- **Frontend:** HTML, CSS, JavaScript (Vanilla)
- **Real-Time:** WebSockets via FastAPI

---

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/chatnest.git
   cd chatnest
   ```

2. **Create and activate a virtual environment (optional but recommended)**
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the FastAPI server**
   ```bash
   uvicorn main:app --reload
   ```

5. **Open the app**
   Go to [http://localhost:8000](http://localhost:8000) in your browser.

---

## 📁 Project Structure

```
chatnest/
├── static/
│   └── script.js        # Frontend JavaScript
├── stylesheet/
│   └── style.css        # Frontend Stylesheet 
├── templates/
│   └── index.html       # Chat UI
├── main.py              # FastAPI backend and WebSocket handling
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

---

## ✨ Future Improvements

- Add private chat rooms
- Store chat history with a database
- User authentication
- Message reactions or emoji support

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 💬 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request with improvements or bug fixes.
