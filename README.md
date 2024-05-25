# QR Code Generator

## Description
This project is a simple web application that generates QR codes based on user input. It uses a public QR code API to create the codes, which can encode text or URLs.

## Features
- **User Input**: Allows users to enter the text or URL they want to encode into a QR code.
- **QR Code Display**: Shows the generated QR code in an image format.
- **Error Handling**: Provides visual feedback if the input field is left empty.

## How to Use
1. Enter your text or URL into the input field.
2. Click the 'Generate QR Code' button.
3. View the generated QR code in the image box.

## Technologies Used
- HTML
- CSS
- JavaScript

## Setup
To run this project, simply clone the repo and open the `index.html` file in a web browser.

## Script Functionality
The `script.js` file contains the `generateQR` function, which:
- Checks if the input field is not empty.
- Generates the QR code using the QR code API.
- Displays the QR code if the input is valid.
- Adds an 'error' class to the input field if it is empty, which is removed after 1 second.

## Repository
The project's repository can be found here.

## License
This project is open-source and available under the MIT License.
