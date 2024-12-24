# Caesar Cipher Encryption and Decryption

This project implements a simple Caesar Cipher encryption and decryption script in Python. The Caesar Cipher is a substitution cipher that shifts the characters of a message by a specified number of positions.

## Features

- Encrypts a message by shifting its characters.
- Decrypts a message by reversing the shift.
- Handles both uppercase and lowercase letters.
- Preserves non-alphabetic characters (e.g., spaces, punctuation).

## Requirements

- Python 3.x

## Installation

1. Clone this repository:
   ```bash
   git clone 
   cd <repository-folder>
   ```

2. Ensure Python 3.x is installed on your system.

## Usage

1. Run the script:
   ```bash
   python caesar_cipher.py
   ```

2. Choose whether to encrypt or decrypt a message:
   - Type `e` to encrypt a message.
   - Type `d` to decrypt a message.

3. Enter your message and the shift value when prompted.

## Example

### Encrypting a Message

Input:
```plaintext
Type 'e' to encrypt a message or 'd' to decrypt a message: e
Enter your message: Hello, World!
Enter the shift value: 3
```

Output:
```plaintext
Encrypted message: Khoor, Zruog!
```

### Decrypting a Message

Input:
```plaintext
Type 'e' to encrypt a message or 'd' to decrypt a message: d
Enter your message: Khoor, Zruog!
Enter the shift value: 3
```

Output:
```plaintext
Decrypted message: Hello, World!
```

## File Structure

```
.
├── caesar_cipher.py          # The main script
├── README.md                 # Project documentation
```

## Limitations

- Only supports the English alphabet (A-Z, a-z).
- Does not handle non-standard shift values (e.g., very large numbers).

## Disclaimer

This script is for educational purposes and is not intended for secure encryption. For secure communication, use established cryptographic methods and libraries.


