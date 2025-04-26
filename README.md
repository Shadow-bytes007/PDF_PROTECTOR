# 🔐 PDF_PROTECTOR – Password-Protect Your PDF from the Command Line

**`PDF_PROTECTOR`** is a lightweight command-line tool that allows you to add password protection to any PDF file in seconds. No GUI, no hassle — just pure terminal power, inspired by Kali Linux-style tools.

---

## ✨ Features

- 🔒 Add password protection to any PDF
- ⚡ Simple and fast CLI interface
- 🐧 Works on any Linux system (Ubuntu, Kali, Debian, etc.)
- 🐍 Built with Python 3 and PyPDF2

---

## 📦 Installation

### 🔧 Step 1: Clone the Repository


```bash
git clone https://github.com/Shadow-bytes007/PDF_PROTECTOR.git
 ```


### 🛠 Step 2: Make Installer Executable and Run It 


```bash
cd PDF_PROTECTOR
chmod +x install_pdfprotector.sh
./install_pdfprotector.sh
```

## 🚀 Usage
### NOW GO TO THE PDF's FOLDER WHICH YOU WANT TO PROTECT


```bash
pdf_protector <input.pdf > <output.pdf > <password >
```
## ✅ Example
```bash
pdf_protector myfile.pdf myfile_protected.pdf mysecret123
```

## 🗂 Notes
### You can provide full or relative paths to the PDF files.

### The script does not require the PDF to be in the same folder as the tool.

### Make sure the input PDF exists and is a valid PDF.

## ❌ Uninstallation
### To remove the tool from your system, run the uninstall script:

```bash
cd PDF_PROTECTOR/
chmod +x uninstall_pdfprotector.sh
./uninstall_pdfprotector.sh
```

### To remove the cloned file 

```bash
cd .. ; rm -r PDF_PROTECTOR && y  
```

## 🧰 Requirements
### Python 3.x

### PyPDF2 library

### If not already installed, the tool will install PyPDF2 automatically via install.sh.

##

## 🪪 License
### This project is licensed under the MIT License.
### Feel free to fork, modify, and share — just give credit where it’s due!

##


## 🙌 Author
### Made with ❤️ by Shadow-bytes007
