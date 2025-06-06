HashPhrase Web App
Overview
This is a custom-built web application that generates a SHA-256 hash from a user-entered phrase, displayed in Base64 format. Built with HTML, Bootstrap, and JavaScript using the Web Crypto API, it offers a simple way to explore cryptographic hashing.
Note: This app creates hashes, not reverses them. Reversing cryptographic hashes like SHA-256 is not possible.
Features

Enter a phrase and generate its SHA-256 hash.
Clean, responsive interface with Bootstrap styling.
Displays the Base64-encoded hash in a pop-up alert.

How to Use

Open index.html in a modern browser (e.g., Chrome, Firefox).
Type a phrase in the input field.
Click "Générer" to create the hash.
View the Base64-encoded result in the alert box.

Requirements

A browser supporting the Web Crypto API.
No external dependencies (Bootstrap loaded via CDN).

Project Structure

index.html: Contains HTML, JavaScript, and Bootstrap styling.
JavaScript functions:
hashPhrase(phrase): Converts the phrase to a buffer and generates a SHA-256 hash.
generateInput(): Processes user input and displays the hash.



Limitations

Only generates hashes, does not reverse them.
Requires Web Crypto API support in the browser.
For educational use; not for sensitive data.

Example

Input: my secret phrase
Output: A Base64-encoded SHA-256 hash, e.g., q1nW1Av0IEBKAUcTzzuxkNYsZb8LzaMrV7J3nZmtFOb=

License
This is my original project, shared for educational purposes. No license specified.
Disclaimer
This app is a learning tool for hashing and does not interact with Bitcoin wallets or blockchains.
