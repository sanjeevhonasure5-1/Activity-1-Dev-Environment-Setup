# Activity 1: C/C++ Development Environment Setup

During the setup, I installed Visual Studio Code, the Microsoft C/C++ extension, and the MinGW-w64 GCC compiler.
Initially, running `gcc` in the terminal failed because the compiler's `bin` folder was not added to the Windows PATH environment variable.
I resolved this by adding the MinGW `bin` directory to System Environment Variables and restarting the VS Code terminal.
After verifying the installation with `gcc --version`, I also hit a "No such file or directory" error because my terminal was in the parent folder instead of the `Activity-1-Dev-Environment-Setup` directory.
Navigating into the correct folder with `cd` allowed `gcc hello.c -o hello.exe` to compile cleanly.
Running `.\hello.exe` then successfully printed "Hello, World!" in the terminal.