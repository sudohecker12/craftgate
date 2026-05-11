# 🟩 CraftGate

> A private Minecraft server portal with real-time chat, user authentication, and an admin panel — built as a single HTML file with zero backend.

![Made with Firebase](https://img.shields.io/badge/Made%20with-Firebase-FFCA28?style=flat&logo=firebase)
![Free to use](https://img.shields.io/badge/Free%20for-10%2C000%20users-00ff88?style=flat)
![License](https://img.shields.io/badge/License-CraftGate--MIT-green?style=flat)

---

## ✨ Features

- ⚔ **Username + Password Login** — clean gate screen with Minecraft aesthetic
- 💬 **Real-time Global Chat** — powered by Firebase Firestore with live updates
- 🖼 **Image Sharing** — attach and send images inline in chat (Discord-style)
- 🛡 **Admin Panel** — add users, delete users, change passwords, view all uploaded photos
- 🔒 **Access Control** — non-admins see a locked screen when trying to access admin panel
- ⛏ **Get Minecraft Guide** — built-in guide for HappyMod, TLauncher PE, and Google Play
- 🌱 **Minecraft Aesthetic** — custom Minecraft font, enchantment font background, grass block favicon
- 📱 **Mobile Responsive** — works on phones and tablets
- 🆓 **Zero Backend** — single `index.html` file, no server needed
- 🌐 **Free Hosting Ready** — deployable on GitHub Pages

---

## 🚀 Deployment

### Requirements
- A [Firebase](https://firebase.google.com) account (free Spark plan)
- A [GitHub](https://github.com) account (for hosting)

### Setup
1. Create a Firebase project and enable **Authentication** (Email/Password) and **Firestore**
2. Copy your Firebase config into `index.html`
3. Set Firestore rules to allow authenticated reads/writes
4. Upload `index.html` to a GitHub repo and enable **GitHub Pages**
5. Add your GitHub Pages URL to Firebase → Authentication → Authorized Domains

Full step-by-step guide available on request.

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML, CSS, Vanilla JavaScript |
| Auth | Firebase Authentication |
| Database | Firebase Firestore |
| Image Storage | Firestore base64 (no Storage bucket needed) |
| Hosting | GitHub Pages |
| Fonts | Minecraft font, Standard Galactic Alphabet (Enchantment) |

---

## 👤 Author

**Vighnesh** (Craftbuddy6317)

- Created for the CraftGate Minecraft server community
- All rights reserved beyond the terms of the CraftGate-MIT License

---

## 📄 License

This project is licensed under the **CraftGate-MIT License**.
Free for personal and commercial use up to **10,000 users**.
Beyond that threshold, prior written permission from the author is required.

See [LICENSE](./LICENSE) for full terms.
