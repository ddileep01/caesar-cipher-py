# caesar-cipher-py

Run here: https://replit.com/@Dileep-KumarK28/caesar-cipher?v=1

Implementation of Caesar Cipher Program in Python
   Aditya Trivedi  |     Dec 13, 2022  |     Time Saved: 0 mins

Caesar CipherTextLettersDecrypt MessagesEncrypt

Overview
We will cover the Python implementation of the Caesar Cipher, a cryptographic technique used to encrypt and decrypt messages. If you are not familiar with this technique, it involves shifting the letters of a message by a certain number of positions. This technique was used by Julius Caesar to send confidential messages, and it is still relevant in modern cryptography. Through this article, you will learn how to implement the Caesar Cipher in Python and use it to encrypt and decrypt messages.

Introduction to Caesar Cipher in Python
Caesar Cipher is one of the most well-known and straightforward encryption methods in cryptography. The shift Cipher, Caesar's Cipher, Caesar shift, and Caesar's code, are some of its alternate names. With this encryption method, each letter in the text must be changed for a certain difference to encrypt our data. Therefore, there is a difference of 1 and a text will follow the same path. So let's take the help of this diagram below to understand this text. As you can see, our Cipher message starts with the letter I. (IFMMP FWFSZPOF).After going through the above-shifted alphabets we can encrypt that the letter H is converted to the Cipher character I.So after decrypting our message** "IFMMP FWFSZPOF"** the output is "HELLO EVERYONE".

![image](https://github.com/ddileep01/caesar-cipher-py/assets/115636822/4c49fd66-8d3a-4da3-8d81-409afd2e093c)


Pre-requisites:
For loop in Pythonord in PythonString in Python

Algorithm of Caesar Cipher in Python
The algorithm of Caesar Cipher holds the following features :Caesar Cipher Technique is a simple and easy method of encryption technique. Every letter in plain text is changed to a letter that appears a certain number of positions farther down the alphabet. The decrypt key is nothing more than the understanding of how the letters were moved during encryption. That was Caesar Cipher's fundamental idea. The algorithm to obtain an encrypted letter will be as follows if we use a mathematical approach:e = (a + n) mod 26where e represents the encrypted letter's place value,a is the actual letter's position value,and n tells us the number of shifts to be done for each letter.

Implementation of Caesar Cipher in Python
Now after having an understanding of Caesar Cipher through proper examples and diagrams, let's take a look at the implementation part of this.

Explanation
Each character in plain text "HELLO EVERYONE" is read one at a time. Transform each character in the provided plain text by the given shift pattern and appropriate rule depending on how the text is encrypted and decrypted. Following the procedure results in the creation of a new string known as Cipher text.

Brute Force Approach to Break Caesar Cipher
There are several ways to crack the Cipher text. One such option is brute force, which includes testing every decryption key that might exist. For a hacker, this method requires little work but it is easy. So after going through all the possible messages, the hacker found out the message "RAW THIS SIDE" was more relevant in comparison to all others. So we can say that 3 is used as a key to encrypt the message.

How to Decrypt Caesar Cipher in Python?
To decrypt the original text, we can build a function that will shift in the opposite direction. But we can make use of the module's cyclic cipher's property. Cipher(n) = De-cipher(26-n)Decryption can be performed using the same function. As an alternative, we will change the shift value to shifts = 26 - shift. Function to decrypt a cipher text is given below:

Output
FAQs
Q: What is Cipher Text Used For?A: Cipher texts are frequently used to encrypt communications to safeguard online conversations. Data from the application layer is encrypted using Ciphers which is done by the transport layer. A message or piece of data that is in plain text has not been secreted. Cipher Text that is also known as Cryptogram is a message that has been altered to make it so that only the intended receivers can read it. To put it another way, it has become a secret.

Caesar Cipher in Python is an easy method to encrypt your message. Letter in a plain given text is changed to a letter that appears a certain number of positions farther down the alphabet. Decrypt key shows the number that how many times letters were shifted during encryption. Brute force method to decrypt the text requires little work but it is easy.

