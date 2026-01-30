# 📚 Past Paper Downloader & Merger

A Python desktop application that lets students **download, organize, and merge Cambridge International A-Level past papers** using a clean graphical interface.

Built with **CustomTkinter** for the UI and **Requests + PyPDF2** for downloading and merging PDFs.

---

## ✨ Features

- 🖥️ User-friendly GUI (no terminal needed)
- 📥 Download A-Level past papers by:
  - Subject
  - Paper number
  - Number of years
- 🗂️ Automatically organizes papers by year
- 📄 Downloads all variants:
  - Feb / March
  - May / June (3 variants)
  - Oct / Nov (3 variants)
- 🧩 Option to merge all papers into a single PDF
- 📊 Live progress tracking support
- 📁 Custom download location

---

## 🧠 How the Project Works

This project consists of **two main scripts**:

1️⃣ GUI Application (Frontend)

- Built using **CustomTkinter**
- Handles:
  - Folder selection
  - Subject & paper selection
  - Year range input
  - Combine-PDF option
  - Progress display

2️⃣ Downloader & Merger (Backend)

- Uses:
  - `requests` to download PDFs
  - `PyPDF2` to merge PDFs
- Downloads **7 papers per year**
- Saves files in a clean directory structure
- Optionally merges all PDFs into one master file

---

## 🛠️ Requirements

- Python **3.8+**
- Required libraries:
  ```bash
  pip install requests PyPDF2 pillow customtkinter

---
## 📎 Supported Subjects (Built-In)
  - Chemistry (9701)
  - Physics (9702)
  - Mathematics (9709)
  - Computer Science (9618)
  - Further Mathematics (9231)
  - Biology (9700)
  - Economics (9708)
---

## ⏳ Project release comming soon 
