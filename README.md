# FMIAS — File Management In A Shell

FMIAS is a simple shell inspired by **MS‑DOS**.
The name **FMIAS** stands for **File Management In A Shell**.

This project provides a lightweight command‑line environment for basic file management operations inside a controlled workspace.

By using this program you agree to the terms described in the **LICENSE** file.

---

# Commands

| Command | Example         | Description                          |
| ------- | --------------- | ------------------------------------ |
| `help`  | `help`          | Shows the list of commands           |
| `dir`   | `dir`           | Lists files in the current directory |
| `mkdir` | `mkdir test`    | Creates a new folder                 |
| `cd`    | `cd test`       | Changes the current directory        |
| `type`  | `type file.txt` | Displays the contents of a file      |
| `edit`  | `edit file.txt` | Creates or edits a file              |
| `exit`  | `exit`          | Closes FMIAS                         |

---

# Installation

## Windows Setup

1. Open **PowerShell** or **Command Prompt**.

2. Run the following command to install **WSL (Windows Subsystem for Linux)**:

```
wsl --install
```

When prompted to create a password, choose something simple that you can remember.

Example images:

<img src="cmd.png" alt="Command Prompt">

Next click compiler.bat and once thats done close the tab and click start.bat

---

# Running FMIAS

Once WSL is installed, navigate to your project directory.

Example:

If your project is located at:

```
C:\Users\zeera\desktop\project
```

Then in Linux the path will be:

```
/mnt/c/Users/zeera/desktop/project
```

Navigate there using:

```
cd /mnt/c/Users/YOUR_USERNAME/your/project/path
```

Example:

```
cd /mnt/c/Users/zeera/desktop/project
```

---

# Start FMIAS

Run the build script:

```
./build.sh
```

This script will:

1. Compile the program
2. Launch FMIAS

---

# Example Usage

```
R:\> mkdir test
R:\> cd test
R:\test> edit notes.txt
R:\test> type notes.txt
```

---

# Project Structure

```
FMIAS
│
├─ environment
│
├─ src
│   ├─ main.cpp
│   ├─ commands.cpp
│   └─ commands.h
│
├─ Makefile
└─ build.sh
```

---

# License

See the **LICENSE** file located in the project root.
"# FMIAS" 
"# NexisCore" 
