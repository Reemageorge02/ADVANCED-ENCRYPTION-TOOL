# ADVANCED-ENCRYPTION-TOOL

*COMPANT* : CODETECH IT SOLUTIONS

*NAME* : N.REEMA OPHIR GEORGE

*INTERN ID* : CT04DL106

*DOMAIN* : CYBER SECURITY

*DURATION* : 4WEEKS

*MENTOR* : NEELA SANTOSH

*DESCRIPTION* : This task focused on developing an Advanced Encryption Tool using Python to securely encrypt and decrypt files with a user-friendly graphical interface. The tool utilizes strong cryptography standards and an intuitive GUI, making it accessible for users to protect their sensitive data without needing technical knowledge. The project was written and tested using Python’s IDLE (Integrated Development and Learning Environment), which made it convenient to develop, run, and debug the program in an interactive manner. The application combines several powerful Python libraries: tkinter, which provides the GUI components like buttons, labels, text fields, and file selection dialogs; cryptography, which supplies secure cryptographic primitives for key derivation and AES encryption; base64 and os for encoding and file path management; and secrets for generating random salt and initialization vectors (IV) required for secure encryption.
The encryption algorithm implemented is AES-256 in CFB (Cipher Feedback) mode, which ensures confidentiality even when encrypting large files or streams. To derive a secure 256-bit encryption key from the user’s password, the tool employs the PBKDF2 (Password-Based Key Derivation Function 2) with SHA-256 hash function and a random salt, strengthening the password against brute-force attacks.
The GUI prompts the user to select a file and enter a password, then allows them to encrypt or decrypt the file with the click of a button. Encrypted files are saved with an .enc extension in a dedicated folder, and decrypted files are restored with a .dec suffix. The tool handles all steps internally — reading the file, generating the salt and IV, deriving the key, performing encryption or decryption, and saving the output — while providing informative messages for successful operations or errors.
By integrating tkinter and cryptography, the project demonstrates how secure encryption can be combined with a simple interface, making it useful for real-world scenarios where file confidentiality is important. The use of IDLE made it easy to write the code and test the GUI interactively while handling cryptographic operations securely. Overall, this project showcases the ability to build secure, usable software tools by combining Python’s standard and third-party libraries in an effective way.

