# Information Hiding in Images
This project is a simple GUI tool for encrypting and decrypting image files using a numeric key. It demonstrates basic image-level encryption by applying an XOR operation to the raw bytes of a .jpg file.

# How it Works
Built with a Tkinter-based desktop interface.

Lets the user select a .jpg image from their file system.

Takes a numeric key from a text box.

Reads the image file as bytes and converts it to a mutable bytearray.

Applies XOR (^) with the given key to every byte in the image.

Saves the modified bytes back to the same file.

Running the process again with the same key restores (decrypts) the original image.

# Features
Minimal, easy-to-understand Python script.

Single window with:

Encrypt button to hide the image content.

Decrypt button to recover the original image using the same key.

Text field to enter the numeric key.

Demonstrates the concept of symmetric encryption using XOR on image data.

# Requirements
Python 3

Tkinter (ships with most standard Python installations)

# How to Run
Save the script file as:

Information Hiding in images - Code.py

Run the script:

python "Information Hiding in images - Code.py"

In the GUI window:

Enter a numeric key (e.g. 123) in the text box.

Click Encrypt and select a .jpg file to encrypt.

To decrypt, enter the same key, click Decrypt, and select the same file again
