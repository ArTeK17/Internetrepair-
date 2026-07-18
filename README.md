![Windows](https://img.shields.io/badge/Platform-Windows-0078D6?logo=windows&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?logo=powershell&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)
![Version](https://img.shields.io/badge/Version-1.0-blue)

# 🌐 InternetRepair

A lightweight Windows utility designed to repair common Internet connectivity issues.

InternetRepair automates several built-in Windows network repair commands, making it easier to restore your connection without using the Command Prompt.

---

## ✨ Features

- 🔄 Flush DNS Cache
  - Clears the DNS resolver cache to fix website loading issues.

- 🌐 Reset Winsock Catalog
  - Resets the Windows Socket API to resolve connectivity problems.

- 📡 Reset TCP/IP Stack
  - Reinitializes the Windows network stack to fix limited or no Internet connectivity.

---

## 🛠 Technologies Used

- **PowerShell**
  - Used to automate Windows networking commands.

- **PS2EXE**
  - Used to convert the PowerShell script into a standalone executable.

---

## 📖 How It Was Built

InternetRepair was created to simplify common Windows network troubleshooting.

Instead of requiring users to open Command Prompt and remember multiple commands, the application executes them automatically through a simple graphical interface.

The project relies entirely on native Windows commands, ensuring compatibility without requiring third-party software.

---

## 📚 What I Learned

Building InternetRepair allowed me to learn:

- PowerShell scripting
- Windows networking commands
- Creating graphical interfaces in PowerShell
- Converting PowerShell scripts into executables
- Designing a simple and user-friendly utility

---

## 🚀 Getting Started

1. Download the latest release.
2. Extract the ZIP archive.
3. Right-click **InternetRepair.exe**.
4. Select **Run as administrator**.
5. Choose the repair option you want to execute.

> Administrator privileges are required because the application modifies Windows network settings.

---

## ⚠ Disclaimer

InternetRepair only executes official Windows networking commands.

No personal data is collected, modified, or transmitted.

---

## 📄 License

This project is open source and available under the MIT License.
