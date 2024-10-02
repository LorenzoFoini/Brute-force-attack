# Brute-force-attack

![alt text](brute-force.jpg)

## Overview

This Jupyter Notebook demonstrates a brute-force attack approach to decrypt a password and messages encoded with simple substitution ciphers, such as the Caesar Cipher in the second example.<br>
The notebook walks through the process of encrypting and decrypting messages using different keys and attempts to crack the encryption without prior knowledge of the encryption key.

## Features:
- **Brute-Force password attack**: Shows how brute-force can be used for obtain a password.
- **Caesar Cipher Encryption**: Shows how to encrypt a message using a Caesar cipher.
- **Brute-Force Caesar Cipher Decryption**: Implements a brute-force approach to find the correct key by trying all possible shifts in the Caesar Cipher (from 1 to 25).

## Structure

The notebook is organized into the following sections:

1. **Brute-Force password attack**: Algorithm which asks the user a password and then finds it with brute-force attemps.
   
2. **Caesar Cipher Encryption Function**: A Python function that takes a plaintext message and a shift key, and returns the encrypted message.

3. **Brute Force Caesar Cipher Decryption Function**: A brute-force attack function that attempts all possible shifts (keys) and displays all potential decrypted messages, allowing you to manually inspect and identify the correct plaintext.

## Requirements

To run the notebook, you will need:
- Python 3.x
- Jupyter Notebook
- Libraries: No special libraries required other than Python built-ins (`itertools` and `string`).

## How to Use

1. Clone or download the repository containing the notebook.
2. Open the notebook using Jupyter:
   ```bash
   jupyter notebook Brute_force_attack.ipynb
3. Follow the cells in the notebook to:
   Perform a brute-force attack to find the user's password.
   Encrypt a message using the Caesar Cipher.
   Perform a brute-force attack to find the correct key and decrypt the message without prior knowledge of the key.
