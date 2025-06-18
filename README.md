# System Monitor Desktop App

## Project Overview

This project is a real-time desktop application that monitors system performance using a graphical interface. It is built with **Python**, **Tkinter**, **psutil**, and **speedtest-cli**. The app displays **CPU usage**, **RAM usage**, **ping**, **internet download speed**, and **upload speed** — all in a clean and user-friendly interface.

---

## Technologies Used

- **Python**: Core programming language used for logic and scripting.
- **Tkinter**: Python’s built-in GUI toolkit used to create the desktop interface.
- **psutil**: Used to access real-time system-level statistics like CPU and RAM usage.
- **speedtest-cli**: A module that fetches internet speed details such as ping, download, and upload speeds.

---

## Features

-  Real-time CPU usage monitoring  
-  Real-time RAM usage tracking  
-  Internet speed test (download, upload, and ping)  
-  Simple and interactive GUI using Tkinter  
-  Custom styling with fonts, colors, and images

---


##  How It Works

1. **System Stats**: The app uses `psutil` to get current CPU and RAM stats from the operating system.
2. **Internet Speed**: The `speedtest` module measures ping, download, and upload speeds.
3. **GUI Display**: All collected data is updated and displayed in real-time using a Tkinter-based interface.
4. **Styling**: Custom fonts, images, and color themes enhance the user experience.
