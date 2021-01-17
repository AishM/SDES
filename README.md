# SDES

In this project, Simplified Data Encryption Standard (S-DES), a Feistel cipher based off DES with a block size of 8-bits and a key size of 10-bits was implemented. To test the system, S-DES test vectors in the S-DES Known Answer Test document were used. Once the implementation was completed, it was used to mount a Meet in the Middle attack to determine the 20-bit key bundle (k1, k2) used in the Double S-DES encryption used in ECB mode to produce the following a specific known plaintext/ciphertext pairs.
A brute force search was implemented to find the key so that the time taken by brute force method and meet in the middle could be compared.
