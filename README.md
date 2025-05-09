# 🔐 Caesar's Encryption - Caesar Cipher with Symbol Substitution

## 📌 Overview
This Python project implements the classic **Caesar Cipher** with an additional security layer through symbol substitution. It provides interactive message encryption and decryption with the option to save results to a file.

## ✨ Key Features
- **Advanced encryption**: Combines alphabetical shift with symbol substitution
- **Interactive process**: User-friendly command line interface
- **Secure storage**: Automatically saves encrypted texts
- **Precise decryption**: Recovers original messages with correct key

## 🛠️ How It Works

### 🔒 Encryption
1. User enters text to encrypt
2. Provides a numeric key (integer)
3. The program:
   - Shifts each letter by the key value (e.g., key 3: 'a' → 'd')
   - Performs additional symbol substitutions
   - Saves encrypted text to file (in documents folder)

### 🔓 Decryption
1. User provides encrypted text
2. Enters the same key used for encryption
3. The program:
   - Reverses symbol substitutions
   - Applies inverse shift (subtracts the key)
   - Displays original message in console

## ⚙️ Technologies Used
- **Python 3** (main language)
- **Standard libraries**: os, string, etc.
- **Storage**: TXT files in documents folder

## 📚 Additional Documentation
- Maintains original letter capitalization
- Non-alphabetic characters remain unchanged
- Circular system (after 'z' returns to 'a')

## 👨‍💻 Developer
**Heitor Carnielo Janko**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/heitor-carnielo-janko-873bb1348/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/HelloBigBoi124)

---

> "Encryption is the art of protecting information - a necessity in the digital age."  
> 🔐 Digital security begins with simple algorithms!
