# Course07 Bank Project & C++ Utility Toolbox

A comprehensive, production-grade C++ banking management system and utility toolkit built as part of advanced foundational software architecture training. This repository features custom, header-only libraries optimizing algorithmic math operations, vector manipulations, safe text handling, data persistence, and secure console-based input/output operations.

---

## 🛠️ Project Structure & Custom Libraries Overview

Unlike standard header implementations, this repository is powered by a suite of **custom-built and heavily modified libraries** designed to extend core C++ functionalities, resolve procedural bugs, and optimize banking business logic:

* **Core Application**: `ConsoleApplication3.cpp` manages the runtime execution and the primary user experience loop for the Bank Management System.
* **Customized Library Stack**:
  * `MyBankDataLib.h`: Custom data-streaming and record-parsing engine managing account serialization with `Clients.txt`.
  * `MyInputLib.h` / `myCpp5AllFuncLib.h`: Deeply refactored, fail-safe validation libraries ensuring robust stream-clearing and type-safe user inputs.
  * `MyStringLib.h`: Enhanced string-manipulation workspace featuring custom-engineered `Trim` algorithms (handling edge cases for empty/space-only buffers).
  * `MyMathLib.h`, `MyArrayLib.h`, `MyVectorLib.h`, `MyUtilityLib.h`: Optimized logical modules tailored to accelerate mathematical computations and memory-safe container wrappers.
---

## 🚀 Getting Started & Compilation

### Prerequisites
Ensure you have a modern C++ compiler supporting at least **C++17** (e.g., GCC/MinGW, MSVC, Clang).

### Manual CLI Compilation
To build and run the executable using the Windows PowerShell environment with GCC, execute the following from the repository root directory:

```bash
# Compile the executable with C++17 standard enabled targeting the current directory include paths
g++ -std=c++17 ConsoleApplication3.cpp -I . -o Course07Bank.exe

# Run the compiled binary on Windows
.\Course07Bank.exe
