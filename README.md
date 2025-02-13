# Build Your Own NGINX Server using NodeJS

## Overview
This project demonstrates how to build a simple NGINX-like server using Node.js. It serves static files such as HTML, CSS, JavaScript, and images, mimicking the behavior of a basic web server.

## Features
- Serves static HTML, CSS, and JavaScript files
- Handles MIME types for various file extensions
- Displays custom 404 error pages
- Lightweight and easy to understand for beginners

## Technologies Used
- Node.js
- HTTP module
- File System (fs) module
- Path module

## Prerequisites
- Node.js installed on your system

## Installation
```bash
# Clone the repository
git clone <repository-url>

# Navigate to the project directory
cd Build-Your-own-NGINX-Server-using-NodeJS

# Install dependencies (if any)
npm install
```

## Usage
```bash
# Start the server
node server.js
```
Open your browser and navigate to `http://localhost:3000` to see the application in action.

## Project Structure
```
Build-Your-own-NGINX-Server-using-NodeJS/
│   server.js
│   index.html
|   contact.html
│   style.css
│   script.js
│   README.md
└───assets/
```

## Issues Faced
- Incorrect MIME type assignment for `.css` files causing styles not to load
- `ENOENT` errors when file paths were incorrect

## WORKING DEMO
![Welcome to custom server - Google Chrome 13-02-2025 12_55_05](https://github.com/user-attachments/assets/4ad1a4d1-515b-4ea1-8146-389ea0ac0f4f)
![Welcome to custom server - Google Chrome 13-02-2025 12_55_16](https://github.com/user-attachments/assets/66fc48d6-58c3-4299-ad41-1e4b3ae7f6e2)

## Remarks
This project is a great starting point for understanding how web servers work under the hood. It can be further extended to include routing, dynamic content, and more advanced features.

## License
This project is open-source and available under the MIT License.

