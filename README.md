# 🐍 Portable Python with Virtual Environment

Run Python scripts using a **portable embeddable Python package** with a **virtual environment**, managed via a **batch file**.  
No system Python installation required.

---

## 📘 Project Overview

This repository provides a **fully portable Python environment**:

- Uses **Python embeddable package**  
- Installs **pip using `get-pip.py`**  
- Installs **virtualenv** to create isolated environments  
- Uses a **batch file (`venv.bat`)** to activate the virtual environment  
- Allows running Python scripts **directly from the repo**  

---

## 🎯 What This Setup Does

When you run `venv.bat`:

1. It activates the virtual environment stored in the repo folder.  
2. The virtual environment was created inside the **embeddable Python** folder.  
3. Python scripts can be executed inside this isolated environment.
4. No changes are made to the host system’s Python or environment variables.

---

## 🧩 Repository Structure

pythin-in-usb/
├── python/ # Python embeddable package
│ ├── python.exe
│ └── DLLs, Lib, etc.
| └── myvenv/ # Virtual environment folder (created once using virtualenv)
| └── get-pip.py # Script to install pip in the embeddable Python
├── venv.bat # Batch file to activate venv
└── README.md

---

## ⚙️ Step-by-Step Usage

### 1. Clone or Download Repository

```bash
git clone https://github.com/harshit404540/python-in-usb.git
cd python-in-usb
```

### 2. Run venv.bat

```bash
Double click on venv.bat to run virtual enviroment/use python from usb.
```

📚 References

```bash
Python: https://www.python.org/downloads/windows
get-pip.py: https://bootstrap.pypa.io/pip/pip.pyz
```

