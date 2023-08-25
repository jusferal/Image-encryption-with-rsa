# Image Encryption with RSA Algorithm

This project focuses on providing a solution for encrypting images in JPG format using the RSA (Rivest-Shamir-Adleman) algorithm. The encryption process is detailed below.

## Encryption Process

1. **Pixel Matrix**: The image is converted into a three-dimensional MxNx3 matrix.

2. **Key Generation**: Public and private keys are generated following the RSA algorithm. 

3. **Pixel Encryption**: Each pixel in the matrix is encrypted using the same private key. 

4. **Image Decryption**: To recover the original image, the public key is used to decrypt the previously encrypted pixels. This process results in the decrypted image.

## Additional Function: Calculate Similarity

In addition to encryption and decryption, an extra function to calculate the similarity percentage has been implemented. This function allows evaluating the similarity between the original image and the encrypted image, as well as the decrypted image with the original one. This feature is valuable for checking the effectiveness of the encryption and decryption process.


## Technologies
* Python

## Creators
[@jusferal](https://github.com/jusferal)
[@luzzka](https://github.com/luzzka)
