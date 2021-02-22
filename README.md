# Cryptography101-[NightNasho]
This is full document of cryptography I have made using my past knowledge and experiences.

![alt text](https://github.com/NashoNightmare/Cryptography101--NightNasho-/blob/master/YW7lEF.jpg)

## Content - Quick Jump

- [![alt text](https://img.shields.io/badge/2.0-Useful%20Websites-orange)](https://github.com/NashoNightmare/Cryptography101--NightNasho-#20-useful-websites-for-deciphering-and-ciphering) 
	- [![alt text](https://img.shields.io/badge/2.1-Dcode.fr-yellow)](https://github.com/NashoNightmare/Cryptography101--NightNasho-#21-dcodefr) 
	- [![alt text](https://img.shields.io/badge/2.2-IMGonline-yellow)](https://github.com/NashoNightmare/Cryptography101-NightNasho#22-imgonline) 
	- [![alt text](https://img.shields.io/badge/2.1-Dcode.fr-yellow)]() 
	- [![alt text](https://img.shields.io/badge/2.1-Dcode.fr-yellow)]() 

- [![alt text](https://img.shields.io/badge/3.0-Interesting%20Ciphers-orange)](https://github.com/NashoNightmare/Cryptography101--NightNasho-#30-interesting-ciphers) 
	- [![alt text](https://img.shields.io/badge/3.1-Brainfuck%20Language-yellow)](https://github.com/NashoNightmare/Cryptography101--NightNasho-#31-brainfuck-language) 
	- [![alt text](https://img.shields.io/badge/3.1-Brainfuck%20Language-yellow)]() 
	- [![alt text](https://img.shields.io/badge/3.1-Brainfuck%20Language-yellow)]() 
	- [![alt text](https://img.shields.io/badge/3.1-Brainfuck%20Language-yellow)]() 

- [![alt text](https://img.shields.io/badge/4.0-Python%20Libraries%20and%20Scripts-orange)](https://github.com/NashoNightmare/Cryptography101-NightNasho#40-python-libraries-and-scripts-useful-for-cryptography-and-steganography)
	- [![alt text](https://img.shields.io/badge/4.1-Pillow%20(Image%20processing%20library)-yellow)](https://github.com/NashoNightmare/Cryptography101-NightNasho#41-pillow-library)

## 2.0 Useful Websites For Deciphering and Ciphering.

### 2.1 Dcode.fr  
Link : [https://www.dcode.fr](https://www.dcode.fr/)

DCode is free and its tools are a valuable help in games, maths, geocaching, puzzles and problems to solve every day.

### 2.2 IMGonline
Link : [https://www.imgonline.com.ua/eng/scan-qr-bar-code.php](https://www.imgonline.com.ua/eng/scan-qr-bar-code.php)

QR and Barcode Scanning tool online. 

## 3.0 Interesting Ciphers

### 3.1 Brainfuck Language
> `Sample` : --[----->+<]>.++++++.-----------.++++++.[----->+<]>.----.---.+++[->+++<]>+.-------.++++++++++.++++++++++.++[->+++<]>.+++.[--->+<]>----.+++[->+++<]>++.++++++++.+++++.--------.-[--->+<]>--.+[->+++<]>+.++++++++.>--[-->+++<]>.

Link for (En/De)Code : [https://www.dcode.fr/brainfuck-language](https://www.dcode.fr/brainfuck-language)

## 4.0 Python Libraries and Scripts useful for Cryptography and Steganography

### 4.1 Pillow Library 
Powerful image processing library. It will help to convert the pixels of a specific image to rgb codes. Furthermore use colormap's rgb2hex to convert those values to hexadecimal.
> pip install Pillow

Documentation : [pillow.readthedocs.io](https://pillow.readthedocs.io/en/stable/)

Image processing tutorials :
- [OpenCV](https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_imgproc/py_table_of_contents_imgproc/py_table_of_contents_imgproc.html)
- [Pillow](https://auth0.com/blog/image-processing-in-python-with-pillow/)

### 4.2 Colormap
Colormap package provides simple utilities to convert colors between RGB, HEX, HUV and a class to easily build colormaps for matplotlib.
> pip install colormap

Documentation : [colormap.readthedocs.io](https://colormap.readthedocs.io/en/latest/)

### 4.3 Binascii 
The binascii module contains number of methids to convert between binary and various ASCII-encoded binary representations. Normally, you will not use these functions directly but use wrapper modules like uu, base64 or binhex instead. The binascii module contains low-level functions written in C for greater speed that are used by the higher-level modules.

Documentation : [Binascii Docs](https://docs.python.org/3/library/binascii.html)

### 4.3 Crypto
Python Cryptography Toolkit. A collection of cryptographic modules implementing various algorithms and protocols.
> pip install pycrypto

Subpackages:

- Crypto.Cipher
	- Secret-key (AES, DES, ARC4) and public-key encryption (RSA PKCS#1) algorithms
- Crypto.Hash
	- Hashing algorithms (MD5, SHA, HMAC)
- Crypto.Protocol
	- Cryptographic protocols (Chaffing, all-or-nothing transform, key derivation functions). This package does not contain any network protocols.
- Crypto.PublicKey
	- Public-key encryption and signature algorithms (RSA, DSA)
- Crypto.Signature
	- Public-key signature algorithms (RSA PKCS#1)
- Crypto.Util
	- Various useful modules and functions (long-to-string conversion, random number generation, number theoretic functions)

Basic  Usage:
> from Crypto.Util.strxor import strxor

Documentation : [Crypto](https://pythonhosted.org/pycrypto/Crypto-module.html)

