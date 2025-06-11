
# 🔐 HashPhrase Web App

A sleek and simple web app that converts any phrase into a **SHA-256 hash**, beautifully displayed in **Base64 format**. Great for learning how cryptographic hashing works — all right in your browser!

> ⚠️ This app **generates hashes only** — it does *not* reverse them (because that’s cryptographically impossible with SHA-256).

---

## ✨ Features

✅ Enter a phrase and generate its SHA-256 hash  
✅ Displays the Base64-encoded hash result  
✅ Clean, responsive UI styled with **Bootstrap 5**  
✅ Lightweight and fast – no backend, no libraries to install

---

## 🚀 Live Demo

To use the app:

1. 📂 Open the `index.html` file in any modern browser  
2. 💬 Type your phrase in the input field  
3. 🔘 Click the **"Générer"** button  
4. 📢 View the Base64-encoded SHA-256 hash in the success alert

---

## 🔍 Example

**Input:**
```
my secret phrase
```

**Output:**
```
q1nW1Av0IEBKAUcTzzuxkNYsZb8LzaMrV7J3nZmtFOb=
```

---

## 🧱 Project Structure

```
📁 index.html
    └── 💡 Contains all HTML, JavaScript logic, and Bootstrap styling
```

### 🧠 Core JavaScript Functions

- `hashPhrase(phrase)`  
  Uses `crypto.subtle.digest` to generate a SHA-256 hash and encode it in Base64.

- `generateInput()`  
  Reads the user input, generates the hash, and displays it in a success alert.

---

## 📋 Requirements

- ✅ A modern browser supporting the **Web Crypto API** (Chrome, Firefox, Edge, etc.)
- 🌐 Internet access (to load Bootstrap via CDN)

---

## ⚠️ Limitations

🚫 This app **cannot reverse hashes** — SHA-256 is designed to be a one-way function  
🚫 Not intended for storing or processing sensitive information  
🚫 May not work in very old browsers (e.g., Internet Explorer)

---

## 👨‍🏫 Educational Purpose Only

This tool is designed for educational use and learning about hashing. It does **not**:

- Interact with 🪙 cryptocurrency or blockchain systems  
- Save or transmit any data over a network  
- Offer secure hashing for passwords or production use

---

## 📄 License

This is my original project, shared freely for learning and experimentation.  
📌 **No license specified** — feel free to fork, improve, and build upon it.

---

## 🙌 Credits

Created with 💙 by **Chedy Chaaben**

If you find this project helpful, feel free to ⭐️ star it or open an issue with feedback!
