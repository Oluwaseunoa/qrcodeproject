QR Code Generator

This project is a simple Node.js application that lets you generate a QR code image from any URL you provide. It also saves the URL into a text file for reference. It's a straightforward way to get started with working on backend development and interacting with the file system.

Features

Prompts you to enter a URL directly in the terminal.

Creates a QR code image (qr_img.png) for the entered URL.

Saves the URL into a text file named URL.txt in the project folder.

What You'll Need

Before you begin, make sure you have the following:

Node.js installed on your system (version 14 or later recommended).

A basic understanding of using the terminal/command line.

Setting It Up

Clone or download this project to your computer.

Open the project folder in your terminal or Visual Studio Code.

Run the following command to install the necessary packages:

npm install

How to Use It

Start the application by running:

node index.js

When prompted, type in a URL (e.g., https://example.com).

The program will:

Generate a QR code image and save it as qr_img.png in the same folder.

Save the entered URL into a text file named URL.txt.

Check the project folder for the two files:

qr_img.png: A QR code image you can scan.

URL.txt: A simple text file containing the URL you entered.

Example Output

After entering the URL https://example.com, the following files will be created:

qr_img.png: A QR code image that you can scan with your phone or any QR code reader.

URL.txt: A text file containing:

https://example.com

Dependencies

This project relies on the following Node.js packages:

inquirer: Used to create a prompt in the terminal for user input.

qr-image: Generates QR code images in various formats.

fs: A built-in Node.js module for interacting with the file system.

Troubleshooting

The prompt isn’t showing in my terminal: This might happen if your terminal doesn’t fully support interactive prompts. Try using a different terminal or check the Inquirer documentation.

Files not saving: Ensure you have write permissions in the project directory.

Why I Built This

This project is a fun and practical way to demonstrate some key backend development concepts. It combines user input, file handling, and generating a useful output in the form of a QR code. It’s perfect for anyone getting started with Node.js or looking to explore simple projects with real-world use.

License

Feel free to use or modify this project as you like. It’s open for learning and sharing.
