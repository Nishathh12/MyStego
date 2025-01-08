**Refer to the pdf for detail presentation**
**MyStego: Secure Information Hiding Using DCT and AES**
**Overview**:  
MyStego is a steganography system that hides secret messages within images using **Discrete Cosine Transform (DCT)** and **Advanced Encryption Standard (AES)**. It combines image processing and cryptography to securely encode and conceal information in a way that is difficult to detect.

**Key Components**:
- **DCT**: Embeds the secret message into the frequency domain of the image, preserving visual quality and making it harder to detect.
- **AES**: Encrypts the message before embedding it into the image, ensuring its confidentiality.
- **Tkinter Interface**: A user-friendly graphical interface to upload images, input messages, and manage encoding/decoding tasks.

**Process**:
1. **Encoding**: The secret message is encrypted using AES, then hidden inside the image using DCT.
2. **Decoding**: The hidden message is extracted by reversing DCT, then decrypted with AES.

