# PassVault - A Cryptographically Secured Password Manager 🔒

PassVault is a password manager built with the MERN (MongoDB, Express, React, Node.js) stack that uses the RSA (Rivest–Shamir–Adleman) cryptographic algorithm for encryption and decryption of user passwords. This application provides a secure and user-friendly interface for storing and managing passwords, ensuring that users can have access to their accounts' credentials with ease.

## 🚀 Features
- 🔒 Secure storage of user passwords in an encrypted database
- 🔐 Use of RSA algorithm to encrypt and decrypt user passwords
- 🌟 Simple and intuitive user interface for easy password management
- 🗝️ Public Private key encrytion for maximum security
- 🚫 Private key is not stored anywhere in our databases

## 💻 Technologies Used
- MongoDB as the database
- Express as the web application framework
- React as the front-end framework
- Node.js as the back-end runtime environment
- RSA module for password encryption and decryption
- Axios for HTTP requests
- JWT for token-based authentication

## 🛠️ Installation
1. Clone the Repository from Github:
```
git clone https://github.com/mayurgalhate/PassVault.git
```
2. Install the required packages in the server and client directories:
```
npm install
npm i
```
3. Run the server:
```
npm start
```
4. Run the client:
```
npm start
```
5. Open your web browser and navigate to http://localhost:3000 to access the password manager.

## 🚀 Usage
- Create an account by providing your email address and a master password.
- Use the password manager to store your usernames and passwords for various accounts.

## 🔐 Security
PassVault uses the RSA algorithm for password encryption and decryption. User passwords are encrypted before storing them in the database and are decrypted when accessed by authorized users. The application also uses Passport.js for authentication, which ensures that only authorized users can access the password manager. JWT tokens are used to authenticate users and authorize their access to the password manager.
