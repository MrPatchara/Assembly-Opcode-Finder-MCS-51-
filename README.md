# 🔍 Assembly Opcode Finder (MCS-51)

<div align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey?style=for-the-badge)

**A powerful desktop application for searching and finding MCS-51 (8051) assembly language opcodes with an elegant vintage-themed interface.**

[Features](#-features) • [Installation](#-installation) • [Usage](#-usage) • [Screenshots](#-screenshots) • [Contributing](#-contributing)

</div>

---

## 📋 Table of Contents

- [About](#-about)
- [Features](#-features)
- [Requirements](#-requirements)
- [Installation](#-installation)
- [Usage](#-usage)
- [Project Structure](#-project-structure)
- [Screenshots](#-screenshots)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

---

## 🎯 About

**Assembly Opcode Finder (MCS-51)** is a desktop application designed to help students, developers, and engineers quickly search and find assembly language opcodes for the MCS-51 (8051) microcontroller family. The application features a beautiful vintage-themed dark interface with golden accents, making it both functional and visually appealing.

This tool is particularly useful for:
- 🎓 **Students** learning MCS-51 assembly programming
- 👨‍💻 **Developers** working with 8051 microcontrollers
- 🔧 **Engineers** needing quick reference for opcodes
- 📚 **Educators** teaching embedded systems

---

## ✨ Features

### 🔎 **Powerful Search Capabilities**
- Search by **Mnemonic** (e.g., MOV, ADD, JMP)
- Search by **Operands** (e.g., A, R0, @R1)
- Combined search for precise results
- Case-insensitive search functionality

### 📊 **Comprehensive Results Display**
- Shows matching opcodes with detailed information
- Displays **Mnemonic**, **Operands**, **Opcode**, and **Bytes** for each result
- Clean, formatted table view

### 🎨 **Beautiful User Interface**
- Vintage dark theme with golden text accents
- Intuitive and user-friendly design
- Professional 8051 IC icon display
- Responsive layout

### 🛠️ **Additional Tools**
- **Integrated Simulator**: Launch EDSIM51DI directly from the application
- **Excel Integration**: Open and view the opcode database in Excel
- **Java Installer**: Built-in Java installation helper for Windows x64
- **Cross-platform Support**: Works on Windows, Linux, and macOS

### ⚙️ **Developer-Friendly**
- Clean, well-documented code
- Easy to customize and extend
- Modular design

---

## 📦 Requirements

### **System Requirements**
- **Python 3.x** (3.6 or higher recommended)
- **Java Runtime Environment (JRE)** (for EDSIM51DI simulator)
- **Operating System**: Windows, Linux, or macOS

### **Python Dependencies**
```
tkinter (usually included with Python)
pandas
openpyxl
Pillow (PIL)
```

---

## 🚀 Installation

### **Method 1: Using Pre-built Installer (Windows)**

1. Download the latest release from the [Releases](https://github.com/MrPatchara/Assembly-subject/releases) page
2. Run the installer: `Assembly Opcode Finder (MCS-51).exe`
3. Follow the installation wizard
4. Launch the application from the Start Menu or desktop shortcut

### **Method 2: Manual Installation**

1. **Clone the repository**
   ```bash
   git clone https://github.com/MrPatchara/Assembly-subject.git
   cd Assembly-subject
   ```

2. **Install Python dependencies**
   ```bash
   pip install pandas openpyxl Pillow
   ```

3. **Ensure required files are present**
   - `Book1.xlsx` - Opcode database
   - `cpu.ico` - Application icon
   - `dev.ico` - Developer window icon
   - `ic_8051.png` - 8051 IC image
   - `pic.png` - Developer photo
   - `edsim51di.jar` - Simulator (optional)
   - `lib/edsim51sh.jar` - Simulator library (optional)

4. **Run the application**
   ```bash
   python "Assembly Opcode Finder (MCS-51).py"
   ```
   Or navigate to the installer directory:
   ```bash
   cd "installer windows version 1.0"
   python "Assembly Opcode Finder (MCS-51).py"
   ```

---

## 💻 Usage

### **Basic Search**

1. **Launch the application**
   - Double-click the executable or run the Python script

2. **Enter search criteria**
   - **Mnemonic**: Type the instruction mnemonic (e.g., `MOV`, `ADD`, `JMP`)
   - **Operands**: Type the operands (e.g., `A`, `R0`, `@R1`)
   - You can search by mnemonic only, operands only, or both

3. **Click "Search"**
   - Results will appear in the results listbox below

4. **View results**
   - Each result shows: Mnemonic, Operands, Opcode (hex), and Bytes

5. **Reset**
   - Click "Reset" to clear all inputs and results

### **Advanced Features**

#### **Run 8051 Simulator**
- Go to **Menu** → **Run 8051 Simulator**
- This will launch the EDSIM51DI simulator (requires Java)

#### **Open Excel Database**
- Go to **Settings** → **Open Excel File**
- Opens `Book1.xlsx` in your default spreadsheet application

#### **Install Java (Windows)**
- Go to **Help** → **Install Java windows x64**
- Launches the Java installer for Windows x64 systems

#### **Contact Developer**
- Go to **Help** → **Contact Developer**
- View developer information and contact details

---

## 📁 Project Structure

```
Assembly-subject/
│
├── README.md                          # This file
├── LICENSE                            # MIT License
│
├── Assembly Opcode Finder (MCS-51).py # Main application (in installer folders)
├── Book1.xlsx                         # Opcode database
│
├── cpu.ico                            # Main application icon
├── dev.ico                            # Developer window icon
├── ic_8051.png                        # 8051 IC image
├── pic.png                            # Developer photo
│
├── edsim51di.jar                      # EDSIM51DI simulator
├── java-installer-windows-x64.exe     # Java installer
│
├── lib/
│   └── edsim51sh.jar                  # Simulator library
│
├── installer windows version 1.0/     # Windows installer v1.0
│   ├── Assembly Opcode Finder (MCS-51).py
│   ├── Assembly Opcode Finder (MCS-51).spec
│   └── ...
│
└── installer windows version beta/    # Beta installer
    └── ...
```

---

## 📸 Screenshots

> **Note**: Screenshots would be added here showing the application interface, search functionality, and results display.

### **Main Interface**
- Vintage dark theme with golden accents
- Clean, professional layout
- Easy-to-use search interface

### **Search Results**
- Formatted table view
- Clear display of opcode information
- Multiple results support

---

## 🤝 Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open a Pull Request**

### **Contributing Guidelines**
- Follow the existing code style
- Add comments for complex logic
- Test your changes thoroughly
- Update documentation if needed

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2024 Patchara Al-umaree

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 📧 Contact

**Developer**: MR. Patchara Al-umaree

- 📧 **Email**: [Patcharaalumaree@gmail.com](mailto:Patcharaalumaree@gmail.com)
- 🐙 **GitHub**: [@MrPatchara](https://github.com/MrPatchara)

---

## 🙏 Acknowledgments

- **EDSIM51DI** - For the excellent 8051 simulator
- **MCS-51 Community** - For inspiration and feedback
- **Open Source Community** - For amazing tools and libraries

---

<div align="center">

**⭐ If you find this project helpful, please consider giving it a star! ⭐**

Made with ❤️ by [Patchara Al-umaree](https://github.com/MrPatchara)

</div>
