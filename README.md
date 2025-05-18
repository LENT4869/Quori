# Quori 🔒

Quori is a security-focused browser built with RPS (Random Passphrase System) authentication before use — made for Web3 users who care about wallet safety.

> 🧠 You will be shown 12 custom mnemonic words on first launch — required to unlock the browser.

---

## ✨ Features

- 🔐 **RPS Authentication Gate**  
  Browser must be unlocked using random 3-of-12 word validation.
  
- 🛑 **Blocks actions before verification:**  
  - Extension usage  
  - DevTools opening  
  - Any URL navigation  
  - App menu (three dots) access  
  - Bookmarks and new tabs  
  - Plugin icon clicks  

- 📜 **Login Records**  
  Successful and failed login attempts are recorded (locally).

- 🛠️ **Secure local storage**  
  Hash of mnemonic is stored in `IndexedDB` with salt. Not sent anywhere.

---
## 🧪 For Web3 Users (Beta Notice)

This is a **beta build**. If you're a Web3 user, please follow these security suggestions:

- Use a **new test wallet** (DO NOT import your real wallet)
- Carefully record the 12 mnemonic words shown on first launch — they won’t be shown again
- If you **reset the RPS**, the mnemonic and verification status will be erased and reinitialized
- Your **local login history** (success/failure) will NOT be cleared during reset


---

## 🪛 Installation

Download latest installer from [Releases](https://github.com/LENT4869/Quori/releases).  
Run it and follow the steps.

---

## 📷 Screenshots

| First Launch | RPS Verification | Unlocked |
| ------------ | ---------------- | -------- |
| *(add here)* | *(add here)*     | *(add here)* |

---

## 📣 Feedback Welcome

Please open an [Issue](https://github.com/LENT4869/Quori/issues) if you encounter bugs, have suggestions, or want to help improve Quori!

---

## 👤 Author

Made by [LENT](https://github.com/LENT4869)  
Inspired by the need for secure access to Web3 environments.

---

## 🪪 License

(c) 2025 LENT — All rights reserved.  
Quori uses the [Chromium Project](https://www.chromium.org/) under the [BSD-3 license](https://chromium.googlesource.com/chromium/src/+/main/LICENSE).
