🧠 LlamaMind 1.0
A lightweight, optimized and secure local LLM runner built on top of llama.cpp.
Designed for LAN usage, performance tuning, and easy deployment.
Built under restricted internet conditions, so it might have some bugs 😅
LlamaMind Tutorial

Powered by llama.cpp (B8639 Vulkan build) ⚡


🚀 Features

Local LLM server using llama.cpp
Built-in authentication system (username/password)
Secure LAN sharing (controlled access)
Adaptive performance optimization (CPU / RAM / VRAM)
Interactive setup system
Supports any GGUF model
Vulkan GPU acceleration
Dynamic tuning:

GPU layers
CPU threads
Context size


Reasoning control (on / off / custom budget)
Lightweight proxy server
Control panel (start / stop / manage users)
Portable structure
Optimized for low and mid-end systems



📦 Requirements

Windows x64
Node.js (v18 or higher)
GPU with Vulkan support (optional but recommended)



⚙️ Installation

Install Node.js
Download or clone this project
Place your GGUF model anywhere on your system



▶️ Usage
WINDOWS :
CMD
.\llamaMind.bat

Then:
Run Setup System
Enter your system specs
Start the server
🔐 Authentication
Users must log in before accessing the model.
You can:
Add users
Delete users
Manage access
🧠 Performance Modes
Balanced → stable + low usage
Max VRAM → maximum speed
Advanced → full control
📁 Structure
llamamind/
│
├── llamaMind.bat
├── llama-auth/
├── llama.cpp/
├── models/
💡 Notes
GPU usage depends on configuration
Higher VRAM usage = higher token speed
Context size affects RAM usage
