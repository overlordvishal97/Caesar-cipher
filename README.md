# Caesar-cipher
This repository contains a simple Caesar cipher program written in Python. The Caesar cipher is a type of substitution cipher in which each letter in the plaintext is shifted a certain number of places down the alphabet.

## Features

- Encrypts and decrypts text using a specified shift value.
- Handles shifts greater than 26 by using modulo arithmetic.
- Retains numbers, symbols, and spaces in the input text.
- Allows users to restart the program to encrypt/decrypt multiple messages.

## How to Run the Program

To run this program, you need Python installed on your computer.

### Steps to Run the Program:

1. Clone this repository to your local machine.
2. Navigate to the cloned directory.
3. Ensure you have the `art.py` file in the same directory with a `logo` variable containing your ASCII art logo.
4. Run the program using Python:

```bash
python caesar_cipher.py

### Usage

When prompted, enter encode to encrypt or decode to decrypt a message.
Enter the message you want to encode or decode.
Enter the shift number (the number of positions each letter in the message will be shifted).
The program will display the encoded or decoded message.
You can choose to run the program again or exit.

### Example

Type 'encode' to encrypt, type 'decode' to decrypt:
encode
Type your message:
hello
Type the shift number:
5
Here's the encoded result: mjqqt

Type 'yes' if you want to go again. Otherwise type 'no'.
no
Goodbye
