# Captcha Solver

## Overview
This project provides a simple captcha solver that can handle both PNG and SVG captcha images. It uses OCR (Optical Character Recognition) to extract text from the images.

## Features
- Supports both PNG and SVG captcha URLs.
- Solves captchas within 15 seconds.
- Displays solved captcha text.

## Installation
1. Clone the repository.
2. Install the required packages:
   ```bash
   pip install requests Pillow pytesseract
   ```

## Usage
1. Create an instance of `CaptchaSolver` with the captcha URL.
2. Call the `solve_captcha` method to get the solved text.

## License
This project is licensed under the MIT License.