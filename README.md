# Ceaser_cipher
---> The most basic and well-known encryption method is the Caesar cipher, sometimes referred to as Caesar shift or Caesar's code. It is a substitution cipher in which the plaintext's letters are all moved up or down the alphabet by certain amounts. The Caesar cipher is named after Julius Caesar, who reportedly used it to communicate with his generals.With only 25 possible keys, this very basic encryption technique is easily cracked by brute force.

Here's how it works: 
Select the shift value. Usually, this is represented by the integer 'k,' which ranges from 1 to 25.Taking a letter from the plaintext, move it 'k' places in the alphabet.
Using a shift of 3, for instance:
'A' becomes 'D'
'B' becomes 'E'
'C' becomes 'F'
 ...
'X' becomes 'A'
'Y' becomes 'B'
'Z' becomes 'C'

Here is how working with the encryption and cecryption ( I have 2 diferent programs one whhich is encrypt.py and another decrypt.py )

--> To encrypt, each letter is replaced with the letter 'k' positions ahead in the alphabet.
(Plain Text) + 'k' positions ---> Encryted text
--> To decrypt, the process is reversed by shifting each letter 'k' positions back. 
(Encrpyted text) - 'k' positions ---> Plain Text
