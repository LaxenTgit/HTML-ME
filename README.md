# 🔐 SecureAuth Challenge

**Difficulty:** Easy  
**Platform:** GitHub Pages (yep, this is a free CTF)  
**Category:** Web / Steganography / Brute Force

---

## 🎯 What is this?

A simple CTF challenge designed for **web pentesters** who want to test themselves outside of TryHackMe and Hack The Box.

A forgotten admin panel was found on an old server. Your mission: log in and capture the flag.

---

## 🚩 Rules

- No SQL injection — pure client-side auth
- Username is not in the code, but it's "in plain sight"
- Password changes every session, 6 digits, numbers only
- Brute force is allowed (and expected :D)
- XSS Attack is allowed :muscle:

---

## 💡 Hints

1. Inspect the source code
2. An image is not always just an image
3. Don't give up starting from 000000

---

## 🛠️ Tools You Might Need

- Browser DevTools (Ctrl+U)
- `zsteg`, `StegSolve`, or your own Python script
- Hydra / Burp Suite / wfuzz
- Patience

---

## 🚀 Start

[https://laxentgit.github.io/HTML-ME/](https://laxentgit.github.io/HTML-ME/)

---

## 🏆 Flag Format

flag{xxxxx_xxxxx_xxxxx_xxxxxx_XXXXXX}

---

Built with ☕ by [@LaxenTgit](https://github.com/LaxenTgit)
