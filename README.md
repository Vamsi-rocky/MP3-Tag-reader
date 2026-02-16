# 🎵 MP3 Tag Reader Project in C

## 📌 Project Overview
MP3 Tag Reader is a C-based application developed to extract and display metadata information stored inside an MP3 file using the **ID3 tag format**. It reads song details such as Title, Artist, Album, and Year by parsing the binary structure of the MP3 file.

---

## 🎯 Features
- Reads ID3v2 tags from MP3 files  
- Displays song metadata clearly  
- Supports common frames like Title, Artist, Album, Year  
- Uses low-level binary file handling in C  

---

## 🛠️ Concepts Used
- File Handling (`fopen`, `fread`, `fseek`, `fclose`)
- Binary Data Parsing
- Strings and Arrays
- Structures and Modular Programming
- Command Line Arguments

---

## ⚙️ How to Compile
Use GCC compiler:

```bash
gcc main.c mp3.c -o mp3tagreader
