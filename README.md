# CryptoFinalProject

Andrew Egly
CS 486
Final Project - Blowfish cipher

a brief description of what your program does

I will be implementing the blowfish cipher, which I learned about while looking up different ciphers for this class. Blowfish is a symmetric-key block cipher, designed in 1993 by Bruce Schneier and included in a large number of cipher suites and encryption products. This program will encrypt/decrypt 8 byte long messages using p-blocks and s-blocks.

Schneier designed Blowfish as a general-purpose algorithm, intended as an alternative to the aging DES and free of the problems and constraints associated with other algorithms.

features of your program

Encryption/Decryption for strings implementing the p-blocks and s-blocks that will encrypt the symmetric keys that would be held by both parties trying to communicate.

limitations of your program

The basic issue with the blowfish cipher is that it relies on both parties knowing the key used for the cipher, unlike public key encryption. This program will only encrypt/decrypt, cannot send to another user. This was made purely to show the implementation of the blowfish cipher. Also this can only encrypt 8-byte chunks of strings at a time. If I continue on this project I would try to parse larger messages and run them through the blowfish cipher.

specify the version of Python used

Python 3.4+ used

libraries used to implement your program

only the basic libraries were used in this implementation of blowfish

a command line help - show examples of all possible command line options

python3 blowfish.py

this should run my program with my test vectors, there are comments that can help you change the vectors to run different tests than I did.

references - documents, websites or source code

introduction to blowfish - https://en.wikipedia.org/wiki/Blowfish_(cipher)

implementation of blowfish found on GitHub - https://gist.github.com/eigenein/a56ce4d572484a582e14

help with symetric keys - https://en.wikipedia.org/wiki/Symmetric-key_algorithm

explanation of s-boxes implementation - https://crypto.stackexchange.com/questions/30919/s-boxes-in-blowfish
