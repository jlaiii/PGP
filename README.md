# 🔐 PGP Key Generator & Friend Manager

[Live Demo](https://jlaiii.github.io/PGP/)

A simple and intuitive web-based tool to generate PGP key pairs, manage friends' public keys, encrypt messages, and decrypt received messages — all right in your browser with no backend required.

---

## Features

- **PGP Key Generation**  
  Create your own RSA 2048-bit PGP key pair with an optional passphrase.

- **Public Key Management**  
  View and copy your public key to share with others.

- **Friend Management**  
  Add and store friends' names and their public keys securely in your profile.

- **Message Encryption**  
  Encrypt messages to your own key or to any friend in your list.

- **Message Decryption**  
  Paste PGP-encrypted messages and decrypt them using your private key and passphrase.

- **Profile Save & Load**  
  Download your entire profile (keys + friends) as a JSON file and load it later.

---

## How to Use

1. **Generate your keys:**  
   Enter your name, email, and optionally a passphrase, then click **Generate Key**.

2. **Manage your public key:**  
   Show or hide your public key and copy it to share.

3. **Add friends:**  
   Input a friend's name and paste their public key, then add them to your friends list.

4. **Encrypt messages:**  
   Select a friend (or none to encrypt to yourself), type your message, and encrypt it.

5. **Decrypt messages:**  
   Paste an encrypted message, enter your passphrase if needed, and decrypt.

6. **Save your profile:**  
   Download your keys and friends as a `.json` file.

7. **Load your profile:**  
   Upload your saved profile file to restore your keys and friends.

---

## Technology

- Pure HTML, CSS, and JavaScript  
- Uses [OpenPGP.js v5.5.0](https://github.com/openpgpjs/openpgpjs) for cryptographic operations  
- Runs entirely client-side in the browser—no server needed

---

## Security Notes

- Your private keys and passphrase never leave your browser; all cryptographic actions happen locally.
- Profile data is stored only in memory or saved by you manually — no backend storage.
- Keep your profile `.json` file secure as it contains your private keys.

---

## Crypto Donations

If you find this tool useful and want to support development, you can send donations to the following addresses:

- **Bitcoin (BTC):** `bc1quk2r3sukuv4pjumjqpj2hjl6lnvkcq6ws7uanl`
- **Litecoin (LTC):** `ltc1qx3lgmqal9ye579ln4z3v9vza27wr6xglv94u4t`
- **Ethereum (ETH):** `0x037a45482e5d0a988AA5ff5F6804DCe3276488D6`
- **Solana (SOL):** `8PzeFDjKUQf9UDY4ezNdG9927wxKmeETTTyvv2GtuK1a`
- **Monero (XMR):** `85QzVMEGFvogZzGUqmB6aQTcLucKKPCSCiP6rAeNN7nMbM9u5EVgGKPXocrxp6FzwKdVGooPHJaKjMyFsA3ma6zJ1yifbPb`

---

## Feedback & Contributions

Feel free to open issues or pull requests on the [GitHub repository](https://github.com/jlaiii/PGP) to improve this project.


---

**Try it out now:** [https://jlaiii.github.io/PGP/](https://jlaiii.github.io/PGP/)
