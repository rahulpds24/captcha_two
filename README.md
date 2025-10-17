# Captcha Solver

This project is a simple captcha solver that supports both PNG and SVG captcha images. It uses Tesseract OCR to extract text from the images.

## Features
- Supports solving of PNG and SVG captcha images.
- Solves captcha within 15 seconds.

## Installation
1. Clone the repository.
2. Install the required packages:
   ```bash
   pip install requests pillow pytesseract
   ```
3. Ensure Tesseract is installed on your system.

## Usage
1. Create an instance of `CaptchaSolver` with the captcha URL.
2. Call the `solve_captcha()` method to get the solved text.

```python
solver = CaptchaSolver('https://example.com/captcha.svg')
print(solver.solve_captcha())
```

## License
This project is licensed under the MIT License.