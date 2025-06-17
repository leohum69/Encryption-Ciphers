# Classical Ciphers Collection

This repository contains implementations of several classical cryptographic ciphers in C++. Each cipher demonstrates a different encryption technique used historically for secure communication.

## 🔐 Cipher Implementations

### 1. Caesar Cipher
- **File:** `Caeser Cipher.cpp`, `Caeser Cipher Crack.cpp`
- **Description:**
  - The Caesar Cipher is a substitution cipher where each letter in the plaintext is shifted by a fixed number of positions down the alphabet. The cracking version attempts to decrypt text without knowing the key by trying all possible shifts.

### 2. Hill Cipher
- **File:** `Hill Cipher.cpp`
- **Description:**
  - The Hill Cipher is a polygraphic substitution cipher based on linear algebra. It uses matrix multiplication to encrypt blocks of plaintext, making it more secure than simple substitution ciphers.

### 3. Playfair Cipher
- **File:** `Playfair Cipher.cpp`
- **Description:**
  - The Playfair Cipher encrypts pairs of letters using a 5x5 matrix of letters constructed from a keyword. It is more secure than monoalphabetic ciphers and was widely used in the early 20th century.

### 4. Singular Columnar Transposition Cipher
- **File:** `Singular Columnar Transposition CIpher.cpp`
- **Description:**
  - This cipher rearranges the characters of the plaintext into columns based on a keyword, then reads the columns in a specific order to produce the ciphertext. It is a type of transposition cipher.

### 5. Substitution Cipher
- **File:** `Substitution Cipher.cpp`
- **Description:**
  - Each letter in the plaintext is replaced with another letter according to a fixed mapping. The mapping can be random or based on a keyword, making frequency analysis more difficult.

### 6. Vigenère Cipher
- **File:** `Vigenere CIphere.cpp`
- **Description:**
  - The Vigenère Cipher is a method of encrypting alphabetic text by using a simple form of polyalphabetic substitution. A keyword is used to determine the shift for each letter, making it more secure than the Caesar Cipher.

---

## 📂 Folder Structure
- Each `.cpp` file contains the implementation and may include sample input/output for testing.

## 👨‍💻 Author
- Mirza Humayun Masood

## 📜 License
This project is for educational purposes. Please contact the author for other uses.
