## AES Encription Management

### Goal
Create a application to encript a plain text using Encription Technique (AES)

### Techniques
AES is the main techinique, beside of that it has:
#### AES-GMC
Provides both confidentiality and data integrity through authenticated encryption. It's a popular choice for modern applications because it's efficient and supports parallel processing. 

#### AES-CBC
A legacy mode that chains together the encryption of each block, making it more resistant to attacks than ECB. However, it can be slower than GCM and is susceptible to padding oracle attacks. 
#### AES-CTR
Treats the encryption as a stream cipher, where each block is encrypted with a unique counter value. CTR mode is known for its speed and ability to be parallelized. 

### How to implement
plain text => AES-GMC + secure key (save in another place) => encrypt text 


