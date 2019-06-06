## Message-Encoder-Decoder

Vigenere Cipher is a method of encrypting alphabetic text. It uses a simple form of polyalphabetic substitution. A polyalphabetic cipher is any cipher based on substitution, using multiple substitution alphabets .The encryption of the original text is done using the [Vigenère square or Vigenère table.](https://en.wikipedia.org/wiki/Vigen%C3%A8re_cipher#/media/File:Vigen%C3%A8re_square_shading.svg)

```
Encryption
The the plaintext(P) and key(K) are added modulo 26.
Ei = (Pi + Ki) mod 26

Decryption
Di = (Ei - Ki + 26) mod 26
```
### Preview
![alt text](https://github.com/PiyushBhangale/Message-Encoder-Decoder/blob/master/Screenshot%20from%202019-06-06%2018-25-59.png)


### Modules used in the project

  - Tkinter  -> GUI toolkit
  - time 
  - datetime  
  - base64   -> Vigenère cipher
