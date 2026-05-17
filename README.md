# 🔐 SecureChat

SecureChat is a fully end-to-end encrypted communication system developed for a cryptography coursework project. It demonstrates secure messaging and file transfer using custom-built cryptographic algorithms implemented from scratch in Python.

---

## 📌 Features

- 🔐 End-to-end encrypted messaging
- 🔁 Hybrid encryption (Symmetric + Asymmetric)
- 🧠 Custom implementation of:
  - XTEA (symmetric encryption)
  - Twofish (symmetric encryption)
  - ElGamal (asymmetric encryption + signatures)
- 🏛️ Simulated Certificate Authority (PKI system)
- 📁 Secure file transfer support
- 🌐 Flask-based web interface
- 📊 Performance analysis for encryption algorithms
- 🔏 Digital signatures for message authentication

---

## 🏗️ System Overview

SecureChat simulates a real-world secure communication system between users (Alice and Bob):

- Messages are encrypted using **XTEA or Twofish**
- Session keys are exchanged using **ElGamal encryption**
- All messages are signed using **ElGamal digital signatures**
- A **Certificate Authority (CA)** validates user identities

---

## ⚙️ Technologies Used

- Python 3
- Flask (Web Framework)
- HTML / CSS / JavaScript
- Custom cryptographic implementations (no external crypto libraries)

---

## 🔐 Cryptographic Components

### Symmetric Encryption
- **XTEA** → Fast encryption for small messages
- **Twofish** → Strong encryption for larger data

### Asymmetric Encryption
- **ElGamal**
  - Key generation
  - Encryption / Decryption
  - Digital signatures

### PKI System
- Certificate Authority (CA)
- Certificate issuance and validation

---

## 🚀 How to Run

```bash
# 1. Install dependencies
pip install flask

# 2. Run the application
python app.py

# 3. Open in browser
http://127.0.0.1:5000
