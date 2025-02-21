# Pixel Manipulation for Image Encryption
# Overview
This project implements a simple image encryption and decryption tool using pixel-wise manipulation with the XOR bitwise operation. The encryption process scrambles pixel values using a numeric key, making the image unreadable until decrypted with the same key.

# Features
✅ Encrypt Images – Uses XOR encryption to alter pixel values.<br>
✅ Decrypt Images – Restores the original image with the correct key.<br>
✅ User-Friendly Interface – Built with tkinter for easy file selection and input.<br>
✅ Fast & Lightweight – Uses OpenCV and NumPy for efficient processing.<br>

# How It Works
Select an image from your system.<br>
Enter a numeric key (0-255).<br>
The tool encrypts the image and saves it as image_encrypted.png.<br>
To decrypt, select the encrypted image and use the same key.<br>
# Installation
Ensure you have Python 3.x installed,
then install the required dependencies:<br>
<b>pip install opencv-python numpy tkinter</b>
# Usage
Run the script:<br>
<b>python image_encryption.py<br>
Choose an image file (.png, .jpg, .jpeg).<br>
Enter a numeric key (e.g., 123).<br>
The encrypted image is saved automatically.<br>
To decrypt, repeat the process with the encrypted image using the same key.</b><br>

# Technologies Used
Python – Core programming language <br>
OpenCV – Image processing <br>
NumPy – Efficient array operations <br>
Tkinter – GUI for file selection and input <br>

# Future Enhancements
-🚀 Implement AES encryption for stronger security <br>
-🚀 Support batch image encryption <br>
-🚀 Improve the GUI interface\n <br>

# Contributing
Fork the repository and submit pull requests! Any suggestions for improvements are welcome.

License
This project is open-source under the MIT License.

