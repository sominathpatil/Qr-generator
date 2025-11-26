# QR Code Generator

A simple and responsive QR Code Generator built using HTML, CSS, and JavaScript.
This tool allows users to enter any text or URL and instantly generate a QR code using the QRCode.js library.

---

## Features

Generate QR codes from text or URLs

Clean and simple UI

Real-time QR rendering

Clear button to reset input and QR preview

Uses lightweight and fast QRCode.js CDN

---

## Preview
```
+---------------------------+
|   QR Code Generator       |
|  [Enter text here...]     |
|   [Submit] [Clear]        |
|   [Generated QR Code]     |
+---------------------------+
```
---
## 📂 Project Structure
```
├── index.html
├── qr generator.css
└── README.md
```
---
## 🛠 Technologies Used

HTML5

CSS3

JavaScript (ES6)

QR code.js CDN

---
## 📜 How It Works

User enters text or a link in the input field.

On clicking Submit, the script:

Clears any previous QR code

Generates a new QR using the QRCode() constructor

Clear button resets both input and QR display

---
### CDN Used
<script src="https://cdn.jsdelivr.net/npm/qrcodejs/qrcode.min.js"></script>

▶️ Usage

### Clone the repository:

git clone https://github.com/sominathpatil/qr-code-generator.git


### Open the project folder:

cd qr-code-generator


Run the project by opening index.html in your browser.
---
## JavaScript Functions
generateQR()

Reads the input

Displays QR code box

Generates QR code using QRCode.js

clearQR()

Clears input field

Removes QR code

Hides QR display box





