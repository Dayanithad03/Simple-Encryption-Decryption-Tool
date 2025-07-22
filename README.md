🔐 File Encryptor & Decryptor using Python

This is a simple Python-based **File Encryption and Decryption** project using the `cryptography` library's **Fernet** symmetric encryption.

📌 Project Description

This script allows users to:
- Encrypt any file securely using a randomly generated key.
- Decrypt the file using the saved secret key.
- Protect sensitive data and ensure data privacy with minimal setup.

The encryption is handled using **Fernet** encryption from the `cryptography` library, which ensures that the data cannot be manipulated or read without the key.

⚙️ Features

- 🔑 Key Generation and Secure Storage
- 🔐 File Encryption with AES
- 🔓 File Decryption with proper key validation
- 🧪 Error handling for invalid key usage or missing files

🛠️ Requirements

- Python 3.x
- `cryptography` library

To install the required library, run:

```bash
pip install cryptography
