# Quori 🔒

Quori is a security-focused browser that requires RPS (Random Passphrase System) authentication before use — built specifically for Web3 users who care about wallet safety.

> 🧠 On first launch, 12 custom mnemonic words will be shown. These are required to unlock the browser.

---

## ✨ Features

- 🔐 **RPS Authentication Gate**  
  The browser can only be unlocked by passing a verification of 3 randomly chosen words from your 12-word phrase.

- 🛑 **Blocks the following actions before successful verification:**  
  - Extension usage  
  - Opening DevTools  
  - Navigating to any URL  
  - Accessing the app menu (three dots)  
  - Bookmarks and new tabs  
  - Plugin icon clicks

- 📜 **Login Records**  
  Both successful and failed login attempts are recorded locally.

- 🛠️ **Secure Local Storage**  
  The mnemonic is hashed with a salt and safely stored on your device. No data is transmitted externally.

---

## 🧪 Beta Version Notes

This is a beta version of Quori. Web3 users should follow these security guidelines:

- Use a brand-new test wallet — do **not** import your real wallet for testing.
- Carefully write down the 12 mnemonic words shown at first launch — they will **not** be shown again.
- If you choose to reset RPS, all stored mnemonics and verification status will be cleared and setup will start over.
- Local login records (successful or failed) are retained even after reset.
- Set Quori as your default browser to ensure link protection.

---

## 🪛 Installation

Download the latest installer from:  
[https://drive.google.com/drive/folders/1iuoVJE6BT_kMrpXn_vz_3OiBVOILLgXm?usp=sharing](https://drive.google.com/drive/folders/1iuoVJE6BT_kMrpXn_vz_3OiBVOILLgXm?usp=sharing)  
Run the installer and follow the on-screen instructions.

---

## 📷 Screenshots

| First Launch 
![螢幕擷取畫面 2025-05-23 084533](https://github.com/user-attachments/assets/c33e17a5-71de-499f-8678-f7214037d922)

|RPS Verification 
![螢幕擷取畫面 2025-05-23 084545](https://github.com/user-attachments/assets/dda7c3c4-8605-4812-8c6d-a4166d91344f)

| Unlocked |
![螢幕擷取畫面 2025-05-23 084838](https://github.com/user-attachments/assets/1e528830-6153-43b2-95aa-a8d8f83002da)


---

## ⚠️ Beta Limitations

Currently in beta, the following elements are still under development:

- 🚧 Icons and branding appearance are not yet fully replaced (some Chromium defaults may still appear)
- 📦 Installer name and icon remain default (this does not affect functionality or verification)

The core security functionality is stable. A complete branding and install experience will be updated in future releases.

---

## 📣 Feedback Welcome

Encounter bugs? Have suggestions?  
Submit issues or feedback via the [Issues Page](https://github.com/LENT4869/Quori/issues).

---

## 👤 Author

Developed by **LENT**  
Inspired by the need for secure Web3 access and wallet safety.

---

## 🪪 License

(c) 2025 LENT — All rights reserved.  
Quori is based on the Chromium project and licensed under the BSD-3 License.
