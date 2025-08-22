# Steganographic-Cryptography-system-for-communication


```
Steganographic_Cryptography_System/
│── Steganography-Web-App-Demo-main/
│   ├── index.html        # Main webpage (frontend interface)
│   ├── script.js         # Core JavaScript logic for steganography & cryptography
│   ├── style.css         # Styling for the web interface
│   └── .vscode/          # VS Code settings (not necessary for deployment)
│       └── settings.json
```


---

# Steganographic Cryptography System

## 📌 Overview

This project is a **Steganographic Cryptography System** that integrates **cryptography** and **steganography** to provide dual-layer security for sensitive data.

* **Cryptography**: Encrypts the input text using a chosen algorithm to ensure confidentiality.
* **Steganography**: Hides the encrypted message inside a digital medium (e.g., image) without affecting its visible quality.

This demo is implemented as a **web-based application** using **HTML, CSS, and JavaScript**.

---

## 🚀 Features

* Encrypts text using a cryptographic algorithm.
* Embeds the encrypted data into an image using steganography.
* Extracts and decrypts hidden messages from the image.
* Simple, user-friendly web interface.
* Secure dual-layer protection for sensitive information.

---


---

## ⚙️ Tech Stack

* **Frontend**

  * HTML5 → For structuring the web interface
  * CSS3 → For styling and layout
  * JavaScript (ES6) → Core logic for encryption, decryption, hiding, and extracting data

* **Cryptography**

  * JavaScript-based encryption algorithms (e.g., substitution/bitwise operations – can be extended to AES, RSA, etc.)

* **Steganography**

  * Pixel manipulation in JavaScript (hiding/extracting text inside image data)


---


## 📂 Project Structure

```
Steganographic_Cryptography_System/
│── Steganography-Web-App-Demo-main/
│   ├── index.html        # Frontend UI  
│   ├── script.js         # Core logic (crypto + steganography)  
│   ├── style.css         # UI styling  
│   └── .vscode/          # Development settings (optional)  
```

---

## 🛠️ Technologies Used

* **Frontend**: HTML, CSS, JavaScript
* **Cryptography**: Implemented in JavaScript
* **Steganography**: Image-based hiding/extraction

---

## 📖 How to Run

1. Download or clone this repository:

   ```bash
   git clone https://github.com/your-username/steganographic-cryptography-system.git
   cd steganographic-cryptography-system/Steganography-Web-App-Demo-main
   ```

2. Open the `index.html` file in your web browser.

3. Use the interface to:

   * Enter a message → Encrypt → Hide inside an image.
   * Upload a stego-image → Extract → Decrypt message.

---

## Demo

<img width="1855" height="600" alt="Screenshot 2025-08-22 125453" src="https://github.com/user-attachments/assets/2dae89e9-a588-4d3e-add4-b222de132449" />

<img width="1779" height="589" alt="Screenshot 2025-08-22 125619" src="https://github.com/user-attachments/assets/207984e2-3f7e-4ab8-b97f-ee4bfb37af44" />


## 🎯 Use Cases

* Secure communication.
* Protecting sensitive data in digital media.
* Academic and research projects on information security.

---

## 📌 Future Improvements

* Support for multiple cryptographic algorithms.
* Support for more file formats (audio, video).
* Cloud-based deployment for real-time usage.

---

## 📜 License

This project is licensed under the **MIT License** – you are free to use, modify, and distribute it.

---


