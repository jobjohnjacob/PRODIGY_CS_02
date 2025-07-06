# PRODIGY_CS_02

Name: JOB JOHN JACOB

Company: PRODIGY

ID: PIT/JUN25/10895

Domian: CYBER SECURITY

Duration: 15TH JUNE 2025 to 15TH JULY 2025

---

OVERVIEW OF THE PROJECT

PROJECT: Simple Image Encryption & Decryption Tool using Pixel Manipulation

---

Overview:

This project demonstrates a basic image encryption and decryption mechanism using pixel-level manipulation techniques in Python. It’s designed to showcase how visual data can be secured using simple operations like pixel value swapping and mathematical transformations (e.g., XOR, addition).

While not intended for production-grade security, this tool is a great introduction to concepts of image-based encryption and reversible transformations.

---

Features:

Encrypt any RGB image using a custom key

Decrypt the encrypted image back to its original form

GUI-based tool (using tkinter) for easy interaction

Supports common formats like .png, .jpg, .jpeg

Lightweight and beginner-friendly

---

How It Works:

The core logic is based on modifying the RGB pixel values using a secret key. The primary operations used include:

XOR Operation: Applies a bitwise XOR with the key to each RGB value.

Pixel Manipulation: Each pixel’s values are altered deterministically, making the process reversible.

---

Technologies Used:

Python 3

Pillow (PIL) for image processing

tkinter for the user interface

3. Run the script: python image_encryptor.py

4. Select an image, enter a secret key (0–255), and click Encrypt or Decrypt
