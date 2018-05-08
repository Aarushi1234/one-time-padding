# one-time-padding
Readme file
Code Description
This code is written to encrypt text using One time padding technique which includes 3 functions basically.
1. Enc() this function is reading the file data from plaintext.txt file and secret key from key.txt file. Then plaintext is xor ed to produce ciphertext in binary context which is saved in ciphertext.txt file
2. Decryption() this function takes the data from ciphertext.txt file and key from key.txt file and converts it into plaintext and stores it is result.txt.
3. KeyGeneration() this function is used to randomly generate keys using Secure Random method which is then converted into binary and as per given security parameter it is between bound [1, 128] where 128 is being is converted into 16 bytes.
Other function that is introduced for CS 6058 format which is implementing frequencychecker on key of size 3 bits to generate random keys and check whether keys generated are uniformly distributed or not.
Language, Version and Operating System version and Compilation Details
Code is written in java 
IDE 8.0.2
OS Linux Mint 
java version "1.8.0_144"
Java(TM) SE Runtime Environment (build 1.8.0_144-b01)
Java HotSpot(TM) 64-Bit Server VM (build 25.144-b01, mixed mode)
Before code execution you need 
Key.txt= for storing secret key (Store 32 bits data)before running of code
Ciphertext.txt= for storing cipher text after generation 
Plaintext.txt= for storing plaintext or message such that message is less than length of key  (store 4 letters such as cats, bats) before running the code
Result= to store end result of decryption or the plaintext.
