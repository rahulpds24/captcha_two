# Captcha Solver

This project is a simple captcha solver that supports both PNG and SVG captcha images. It utilizes the Tesseract OCR engine to extract text from the images.

## Features
- Supports solving captchas from both PNG and SVG formats.
- Solves captcha within 15 seconds.

## Installation
1. Clone the repository.
2. Install the required packages:
   ```bash
   pip install requests Pillow pytesseract
   ```
3. Ensure Tesseract is installed on your system.

## Usage
1. Create an instance of `CaptchaSolver` with the captcha URL.
2. Call the `solve_captcha` method to get the solved text.

## License
This project is licensed under the MIT License.