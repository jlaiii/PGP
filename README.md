# 🔐 PGP Tools

A simple, clean, and modern collection of web-based PGP tools for securely generating, encrypting, decrypting, and managing PGP keys — all in your browser, with no server interaction.

## 🌐 Live Demo

> Load `index.html` in your browser to access the full toolkit.

## 🧰 Features

- **PGP Key Generator** (`pgpgen.html`)  
  Generate RSA public and private key pairs. Option to show/hide private key, copy to clipboard, and download as JSON.

- **Encrypt Message** (`encrypt.html`)  
  Encrypt a message using a friend's public key. Clean UI with copy-to-clipboard and 30-second auto-clear feature.

- **Decrypt Message** (`decrypt.html`)  
  Paste your private key and a message to decrypt it securely in your browser.

- **Contacts Manager** (`contacts.html`)  
  Import/export public key files. Organize and load public keys for quick encryption.

## 🗂 File Structure

```
📁 /your-repo
├── index.html           # Homepage linking to all tools
├── pgpgen.html          # Key generator tool
├── encrypt.html         # Message encryption tool
├── decrypt.html         # Message decryption tool
├── contacts.html        # Manage public key contacts
└── README.md            # You're reading it!
```

## ⚙️ Tech Stack

- HTML5 + CSS3
- Vanilla JavaScript
- [OpenPGP.js](https://github.com/openpgpjs/openpgpjs) (v5.5.0)

> All operations run **entirely in-browser**. No data is ever sent to a server.

## 📦 Setup

Clone this repo and open `index.html` in your browser:

```bash
git clone https://github.com/yourusername/pgp-tools.git
cd pgp-tools
open index.html  # or just double-click it
```

> 💡 No build step or server required — this is a fully static project.

## 🔐 Why PGP?

PGP (Pretty Good Privacy) allows for secure communication using public/private key encryption. These tools make it easier to use PGP for personal or small-team encryption workflows.

## 📄 License

MIT License — free to use, modify, and distribute.

---

> Created with ❤️ to make PGP easy and accessible for everyone.
