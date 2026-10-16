# 🔐 Secret Message Encryption & Decryption Tool

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white)
![Tkinter](https://img.shields.io/badge/GUI-Tkinter-orange?style=for-the-badge)

> A sleek, beginner-friendly desktop app to **encrypt** and **decrypt** your secret messages using Base64 encoding — protected by a secret key. 🕵️‍♂️

---

## ✨ Features

- 🔒 **Encrypt** any text message into an unreadable Base64 string
- 🔓 **Decrypt** encoded messages back to their original form
- 🎨 **Clean GUI** built with Tkinter — no browser needed
- 🛡️ **Password Protected** — requires a secret key to perform operations
- 🧹 **Reset Button** to quickly clear inputs
- ⚡ **Lightweight & Fast** — runs instantly on any machine with Python

---

## 📸 Preview

| Encrypt | Decrypt |
|---------|---------|
| Turns your message into a secret code 🔴 | Restores the original message 🟢 |

---

## 🚀 Getting Started

### Prerequisites

- Python **3.x** installed on your system
- Tkinter (comes pre-installed with most Python distributions)

If Tkinter is missing (Linux users), install it via:
```bash
sudo apt-get install python3-tk
```

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/Secret-Message-Encryption-and-Decryption-Tool.git
   cd Secret-Message-Encryption-and-Decryption-Tool
   ```

2. **Run the app**
   ```bash
   python Secret_message_encryption_and_decryption.py
   ```

---

## 🎮 How to Use

1. **Launch** the application — a window titled *"Talha's Message Encryption"* appears.
2. **Enter your message** in the top text box.
3. **Enter the secret key** (default: `1234`).
4. Click:
   - 🔴 **Encrypt** → get the Base64-encoded secret message
   - 🟢 **Decrypt** → decode a previously encrypted message
   - 🔵 **Reset** → clear all fields and start fresh

> ⚠️ **Note:** The default password is `1234`. Change it in the source code for real security.

---

## 🧠 How It Works

This tool uses Python's built-in `base64` module to encode and decode messages:

```python
# Encryption
encoded = base64.b64encode(message.encode("ascii")).decode("ascii")

# Decryption
decoded = base64.b64decode(message.encode("ascii")).decode("ascii")
```

The GUI is powered by `tkinter`, with a simple password check gating both operations.

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Language | Python 3 |
| GUI | Tkinter |
| Encoding | Base64 |
| Platform | Cross-platform (Windows / macOS / Linux) |

---

## 📂 Project Structure

```
Secret-Message-Encryption-and-Decryption-Tool/
│
├── Secret_message_encryption_and_decryption.py   # Main application
└── README.md                                     # You're here!
```

---

## 🔮 Future Improvements

- [ ] 🔑 Custom user-defined password (no hardcoded key)
- [ ] 🔐 AES / Fernet encryption for real security
- [ ] 💾 Save encrypted messages to file
- [ ] 🌙 Dark mode toggle
- [ ] 📋 Copy-to-clipboard button
- [ ] 📦 Package as `.exe` for Windows

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork this repo 🍴
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request 🚀

---

## ⚠️ Disclaimer

This project uses **Base64 encoding**, which is **not true encryption** — it's an encoding scheme. Anyone can decode it without the key if they know how. This tool is intended for **educational purposes** and **fun**. For real security, use AES or Fernet encryption.

---

## 👨‍💻 Author

**Minhaz**

- ⭐ If you found this useful, give it a star!
- 🐛 Found a bug? Open an issue.

---

<p align="center">
  Made with ❤️ and Python 🐍
</p>
