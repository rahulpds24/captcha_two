# Captcha Solver

This project is a simple captcha solver implemented using JavaScript and HTML. It retrieves a captcha image from a provided URL and displays the solved text within 15 seconds.

## Features
- Displays captcha image from a URL passed as a query parameter.
- Simulates captcha solving and displays the solved text.
- Default to a sample captcha image if no URL is provided.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/captcha_solver.git
   cd captcha_solver
   ```
2. Open `index.html` in your web browser.

## Usage
- To use the captcha solver, provide a URL to a captcha image as a query parameter:
  ```
  index.html?url=https://example.com/captcha.png
  ```
- If no URL is provided, it will default to `attachments/sample.png`.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.