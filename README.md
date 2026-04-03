1. Project Title:
-> Steganography Project (LSB Image Encoding & Decoding)
   
2. Description:
->This project implements Image Steganography using the Least Significant Bit (LSB) technique. 
->It allows users to hide secret messages inside an image and retrieve them later without noticeable changes to the image.

3. Features:
- Hide secret text inside an image
- Extract hidden message from image
- Uses LSB (Least Significant Bit) technique
- Supports BMP/PNG images
- Simple and efficient implementation in C
  
4. How It Works:
 Working Principle
- Each pixel in the image contains RGB values.
- The least significant bits of these values are modified to store secret data.
- Since the change is minimal, the image looks unchanged to the human eye.

5. Applications
- Secure communication
- Digital watermarking
- Data hiding
- Cybersecurity

6. Future Enhancements:
- Support for more image formats (JPEG, PNG)
- Encrypt message before hiding
- GUI-based interface
- Larger data support
