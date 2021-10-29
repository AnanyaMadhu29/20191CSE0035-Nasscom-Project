## 20191CSE0035-Nasscom-Project
**ANANYA MADHU 20191CSE0035**

Nasscom Project - Cybersecurity (Data Encryption)

## Caesar Cipher in Python

This project is to demonstrate the workings of Caesar Cipher in Python. The given code can be used for the encryption of strings containing alphabets only.

### What is Caesar Cipher?
Caesar Cipher is one of the simplest and most widely known encryption techniques in cryptography. It is also known as Caesar’s cipher, the shift cipher, Caesar’s code or Caesar shift. It is a type of substitution cipher in which each letter in the plaintext is 'shifted' a certain number of places down the alphabet. For example, with a shift of 1, D would be replaced by E, E would become F, and so on. The method is named after Julius Caesar, who seemingly used it to converse with his generals.

#### Example:
Suppose we a have text “presidency university” to be encrypted. We can replace each letter present in the text by another letter having fixed difference. Let’s say we want to right shift by 2 then each letter of the above text has to be replaced by the letter positioned second from the letter.

 **Plaintext:** presidency university
 
**Ciphertext:** rtgukfgpea wpkxgtukva

It is easy to see how each character in the plaintext is shifted up the alphabet. Decryption is just as easy, by using an offset of -2.

### Mathematical Description 
First we translate all of our characters to numbers, 'a'=0, 'b'=1, 'c'=2, ... , 'z'=25. We can now represent the Caesar Cipher encryption function, e(x), where x is the character we are encrypting, as:

![image](https://user-images.githubusercontent.com/93252589/139453565-db0a5031-dfde-4ac8-ab01-b4e3bf898b9b.png)

Where k is the key (the shift) applied to each letter. After applying this function the result is a number which must then be translated back into a letter. The decryption function is :
 
![image](https://user-images.githubusercontent.com/93252589/139453588-b99aa891-2b27-4de7-96fe-41bed766cd81.png)
