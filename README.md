# Classical Cryptography Toolkit

A Tkinter-based educational toolkit implementing:

1. Caesar Cipher
2. Monoalphabetic Cipher
3. Playfair Cipher
4. Hill Cipher
5. Vigenere Cipher
6. One-Time Pad
7. Rail Fence Cipher
8. Columnar Transposition Cipher

## Requirements

- Python 3.10+ recommended
- Tkinter (normally included with standard Windows Python)

No third-party Python packages are required.

## Run

Open a terminal in this folder:

```powershell
python main.py
```

## First test

Cipher: Caesar Cipher
Operation: Encrypt
Input:

NETWORK SECURITY

Key:

5

Expected output:

SJYBTWP XJHZWNYD

Then switch to Decrypt, enter the ciphertext, keep key 5, and decrypt.

## Features

- GUI
- Encryption and decryption
- Random key generation where appropriate
- File open/save
- Copy result
- Execution-time display
- Input validation
- Error dialogs
- Algorithm information panel

## Project structure

Classical-Cryptography-Toolkit/
├── main.py
├── README.md
├── requirements.txt
├── src/
│   ├── __init__.py
│   ├── ciphers/
│   └── ui/
└── data/
    ├── input/
    └── output/
