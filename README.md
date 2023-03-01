# ECDSADip
College project of 2023
This code is not written by me for references you can go to https://www.geeksforgeeks.org/blockchain-elliptic-curve-digital-signature-algorithm-ecdsa/ 
Explanation:
The python code first generates both the private key and the public key.
The calculation is then done by converting the message(as i take the message ECDSA Cde by mee)  to an integer.
The hashing method is used to determine the values of r and s.
Then the signature process takes places
The ApplyDoubleAndAdd method is used to calculate the value of points p1 and p2.
The signature is valid if both points p1 and p2 are equal; else, it is invalid.
