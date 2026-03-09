# Terminal WhatsApp: Console-Based Messaging System

## Description
This repository contains a standalone C++ console application that simulates a WhatsApp-like messaging system. Developed according to a formal Software Requirements Specification (SRS), the project serves as a practical implementation of object-oriented programming (OOP) concepts, class relationships, and dynamic memory management. It features a menu-driven terminal interface that supports user registration, one-on-one private messaging, and administrative controls for group chats. To strictly adhere to the design constraints, all data is handled efficiently in-memory during runtime without the use of external libraries or file persistence.

## Features
* **User Management:** Create accounts, securely log in, and manage profiles with automated "last seen" timestamps.
* **Private Chats:** One-on-one conversations featuring a simulated typing indicator.
* **Group Chats:** Multi-user environments with administrative privileges, allowing admins to manage participants and update group descriptions.
* **Rich Messaging:** Send texts that automatically parse text-based emoticons (e.g., `:)`, `<3`) into emojis. Messages can be replied to and deleted by the sender.
* **In-Memory Storage:** Designed for high performance during a single session, supporting up to 100 users and 1000 messages purely in RAM.

## System Requirements
* **Operating System:** Windows, Linux, or macOS.
* **Compiler:** Any C++ compiler supporting C++11 or later (e.g., GCC, Clang, MSVC).

## Installation & Execution
1. **Clone the repository** or download the source code to your local machine.
2. **Open your terminal** and navigate to the directory containing the file.
3. **Compile the code** using the following command:
   ```bash
   g++ -std=c++11 app.cpp -o whatsapp_app