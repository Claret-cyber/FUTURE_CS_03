# FUTURE_CS_03
Secure File Sharing System with AES encryption (Task 3 – Future Interns)
#  FUTURE_CS_03 - Secure File Sharing System

This project is part of my Future Interns Cybersecurity Internship Task 3.

##  Objective

To build a secure file sharing portal using Flask and AES encryption that allows encrypted upload and secure download of files.

##  Technologies

- Python 3
- Flask
- PyCryptodome
- HTML/CSS (Frontend)
- Git & GitHub

##  How It Works

- Files uploaded through the UI are encrypted using AES and stored in `/uploads`.
- Users can request to download the original file by entering the filename.
- The app decrypts and serves the original file securely.

##  How to Run

```bash
git clone https://github.com/YOUR-USERNAME/FUTURE_CS_03
cd FUTURE_CS_03
python3 app.py
