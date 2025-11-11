<h1 align="center">🪞 Palindrome 🪞</h1>
<p align="center">
  <b>A lightweight Node.js API that checks if a word or phrase is a palindrome.</b><br>
  <i>No frameworks. Pure Node.js. Deployed on Render.</i>
</p>

<p align="center">
  <a href="https://github.com/AngelBelRoth/server-palindromes/stargazers">
    <img src="https://img.shields.io/github/stars/AngelBelRoth/server-palindromes?style=flat-square&color=ff69b4" alt="Stars" />
  </a>
  <a href="https://github.com/AngelBelRoth/server-palindromes/issues">
    <img src="https://img.shields.io/github/issues/AngelBelRoth/server-palindromes?style=flat-square&color=blueviolet" alt="Issues" />
  </a>
  <a href="https://server-palindromes.onrender.com">
    <img src="https://img.shields.io/badge/Live-Demo-success?style=flat-square&logo=render&logoColor=white" alt="Live Demo" />
  </a>
</p>

---

## Overview

**Server Palindromes** is a minimalistic backend API built with **pure Node.js** — no frameworks, no clutter.  
It analyzes input text and determines if it’s a **palindrome** (reads the same backward and forward).

*Perfect for learning about string manipulation, HTTP servers, and clean API design.*

---

## ⚙️ Features

- 🔹 **Lightweight** — built without Express or frameworks  
- 🔹 **Fast** — simple HTTP server  
- 🔹 **Reliable** — deployed on [Render](https://render.com)  
- 🔹 **JSON API** — clean, modern responses  

---

<img width="1600" height="780" alt="Screenshot 2025-11-10 at 20 08 39" src="https://github.com/user-attachments/assets/f139c42e-5365-461b-b0d9-9d65600f0dda" />

---

## 📦 Installation

Clone and run the project locally:

```bash
# Clone the repository
git clone https://github.com/AngelBelRoth/server-palindromes.git

# Enter the project folder
cd server-palindromes

# Install dependencies
npm install

node server.js

http://localhost:8002

GET /check?text=madam

{
  "text": "madam",
  "isPalindrome": true
}

server-palindromes/
├── server.js        # Main Node.js server
├── package.json     # Dependencies and metadata
└── README.md        # Documentation


