
# 🚀 Firsttesting  
*A minimal C++ CLI Hello World application for learning or demonstration purposes.*

---

## 📌 Overview

This is a simple command-line interface (CLI) “Hello World” program written in C++. It serves as a beginner-friendly example to demonstrate basic compilation and execution using the `g++` compiler.

Perfect for:
- Learning how to compile C++ programs from the terminal
- Testing your local development environment
- Serving as a template for larger projects

---

## ⚙️ Prerequisites

Before running this project, ensure you have:

✅ **GNU Compiler Collection (`g++`)** installed on your system.

### 🔧 How to Install `g++`

#### Linux (Debian/Ubuntu):
```bash
sudo apt update && sudo apt install g++
```

#### macOS (with Homebrew):
```bash
brew install gcc  # installs g++ as `g++-13` or similar; check with `g++ --version`
```

#### Windows:
Install [MinGW-w64](https://www.mingw-w64.org/) or [MSYS2](https://www.msys2.org/), then add the `bin` directory to your PATH. Verify with:
```bash
g++ --version
```

> 💡 If `g++` isn’t recognized, restart your terminal after installation!

---

## ▶️ Running Locally

Choose the section below based on your operating system.

---

###  Unix-like Systems (Linux / macOS)

```bash
# Compile the program
g++ Main.cpp -o hello_world

# Make it executable (optional on some systems)
chmod +x hello_world

# Run the application
./hello_world
```

💡 *Expected output:*
```
Hello, World!
```

*(The exact message depends on what’s inside `Main.cpp`.)*

---

###  Windows

```bash
# Compile the program (note: .exe extension required)
g++ Main.cpp -o hello_World.exe

# Run the application
.\hello_World.exe
```

> ⚠️ On Windows, always use `.exe` in both the output filename and execution command. Also, if you’re in PowerShell or CMD, you may need to prefix with `.\` to run executables from the current directory.

💡 *Expected output:*
```
Hello, World!
```

---

## 📁 Project Structure

```
Firsttesting/
├── Main.cpp          ← Your source code
├── README.md         ← This file
└── EXE/              ← Optional: compiled binaries (if included)
```

---

## 🛠️ Customization Tips

Want to change the greeting? Edit `Main.cpp`:

```cpp
#include <iostream>
using namespace std;

int main() {
    cout << "Hello, Developer!" << endl;
    return 0;
}
```

Then recompile and run!

---

##  Contributing

Since this is a personal/test project, feel free to fork, modify, and learn from it. Pull requests are welcome if you’d like!

---

## 🌟 Show Some Love

If you found this helpful, consider starring ⭐ this repository — it helps others discover it too!
