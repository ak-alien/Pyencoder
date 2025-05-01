# 🛡️ PyEncoder - Python Script Obfuscator

**PyEncoder** is a multi-layer Python script obfuscator designed to encode `.py` files using combinations of `marshal`, `zlib`, and various base encodings like `base16`, `base32`, and `base64`.

> 🚀 Compatible with **Windows**, **Linux**, and **Android (Termux)**

---

## 📲 Features

- Encode Python code using:
  - `marshal`, `zlib`, `base16`, `base32`, `base64`
  - Combined and nested encoding options
- 5-layer deep **Simple Encode** mode
- Reverse string and numeric obfuscation
- File size display after encoding
- `.pyc` compilation (for Simple Encode)

---

## 🖥️ Installation

### ✅ Requirements

- Python 3.x

### 📦 Clone the Repository

```bash
git clone https://github.com/ak-alien/Pyencoder
cd Pyencoder
```

---

## **1. Install Git and Python**


- 📱 Termux (Android)

```bash
pkg update
pkg upgrade -y
pkg install python git
```

- 🖥️ Windows

    - [Download and install Git](https://git-scm.com/download/win)
    - [Download and install Python](https://www.python.org/downloads/windows/)

- 🐧 Linux

```bash
sudo apt update
sudo apt install git python3 -y
```

### Run

```bash
python encoder.py
```

---

## 🔐 Encoding Options

| Option | Encoding Combination                  |
|--------|----------------------------------------|
| 01     | Marshal                               |
| 02     | Zlib                                  |
| 03     | Base16                                |
| 04     | Base32                                |
| 05     | Base64                                |
| 06     | Zlib → Base16                         |
| 07     | Zlib → Base32                         |
| 08     | Zlib → Base64                         |
| 09     | Marshal → Zlib                        |
| 10     | Marshal → Base16                      |
| 11     | Marshal → Base32                      |
| 12     | Marshal → Base64                      |
| 13     | Marshal → Zlib → Base16               |
| 14     | Marshal → Zlib → Base32               |
| 15     | Marshal → Zlib → Base64               |
| 16     | Simple Encode (5 Loops + Obfuscation) |
| 17     | Exit                                  |

---

## 📂 Output

- The encoded file is saved as:
  ```
  yourfile_enc.py
  ```
- For **Simple Encode**, the script is also compiled to `.pyc`.

---

## ⚠️ Disclaimer

This tool is for **educational** and **obfuscation** purposes only. It **does not encrypt** code or protect it from reverse engineering. Do **not** use it for malicious activities.

---

##  ✅License

This project is licensed under the **MIT License**.

---

## 🗰️ Stay Obscure. Stay Safe.

