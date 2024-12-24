# Python Projects Collection

This repository contains a collection of Python scripts that demonstrate various functionalities, including keylogging, password strength assessment, image encryption and decryption, and Caesar Cipher encryption and decryption.

## Projects

### 1. Keylogger using `pynput`
A simple keylogger built with Python and the `pynput` library to capture and log keyboard inputs.

**Features:**
- Logs all key presses, including special keys.
- Saves captured keystrokes to a text file (`keylog.txt`).
- Stops logging when the `Esc` key is pressed.

**Usage:**
Run the script to start logging keystrokes:
```bash
python keylogger.py
```

[Detailed Documentation](keylogger/README.md)

---

### 2. Password Strength Assessor
A Python script to evaluate the strength of a password based on various criteria and provide feedback for improvement.

**Features:**
- Categorizes password strength as Very Weak, Weak, Moderate, Strong, or Very Strong.
- Provides actionable feedback for weak passwords.

**Usage:**
Run the script and input a password to assess its strength:
```bash
python password_strength_assessor.py
```

[Detailed Documentation](password_strength/README.md)

---

### 3. Image Encryption and Decryption
Encrypts and decrypts images using a random pixel swapping algorithm based on a user-defined key.

**Features:**
- Encrypts an image by randomly swapping pixel values.
- Decrypts the image to its original form using the same key.

**Usage:**
Encrypt an image:
```python
encrypt_image('input_image.png', 'encrypted_image.png', key=12345)
```
Decrypt an image:
```python
decrypt_image('encrypted_image.png', 'decrypted_image.png', key=12345)
```

[Detailed Documentation](image_encryption/README.md)

---

### 4. Caesar Cipher Encryption and Decryption
Implements a simple Caesar Cipher for encrypting and decrypting messages.

**Features:**
- Encrypts a message by shifting its characters.
- Decrypts a message by reversing the shift.
- Preserves non-alphabetic characters (e.g., spaces, punctuation).

**Usage:**
Run the script and follow the prompts to encrypt or decrypt a message:
```bash
python caesar_cipher.py
```

[Detailed Documentation](caesar_cipher/README.md)

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/GokulCSECS/Prodigy-InfoTech/tree/main
   cd <repository-folder>
   ```

2. Install any required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Disclaimer

These scripts are for educational purposes only. Use responsibly and ensure compliance with applicable laws and regulations. Unauthorized use of these tools may be illegal.



