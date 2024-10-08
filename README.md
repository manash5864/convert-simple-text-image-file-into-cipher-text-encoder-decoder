# convert-simple-text-image-file-into-cipher-text-encoder-decoder

This project is a web-based application that enables users to encrypt text and convert into cipher text and same decrypt the cipher text convert into simple text using RSA algorithm, encrypt images using the RC4 encryption algorithm, and file encrypt as well.The application provides a user-friendly interface to upload an image (in formats like `.jpg`,`.jpeg`or `.png`), encrypt the image's content, and convert it into a ciphertext format, which is displayed in a text area on the screen. 
Key Features:
1.Text converter: here the user can convert the simple text into cipher text using RSA algorithm.
2.Image Upload: Users can select an image from their local device using a file input field.
3.RC4 Encryption: The selected image content is encrypted using the RC4 algorithm. 
4.Ciphertext Output: The encrypted content (ciphertext) is displayed in a read-only text area, allowing users to view the result of the encryption process.
5.FileReader API: The project utilizes the FileReader API to read the image as a data URL (Base64 encoded string) for encryption.
Use Cases:
- This project can be used for securing image data by converting it into an unreadable encrypted format.
- It demonstrates how to apply cryptographic algorithms like RSA to text data,RC4 to image data and filedata, which can later be decrypted if needed.
