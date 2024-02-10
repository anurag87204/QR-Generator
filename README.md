# QR-Generator

QR-Generator is a simple Python script that generates QR codes from user-provided text or URLs. It utilizes the `qrcode` library to create QR codes quickly and efficiently.

## Features

- Generate QR codes for text or URLs.
- Customize QR code size, color, and error correction level.
- Save generated QR codes as PNG images for easy sharing and usage.

## Installation

1. Clone the repository:

bash
git clone https://github.com/anurag87204/QR-Generator.git

2. Install the required dependencies:

bash
pip install -r requirements.txt

## Usage

1. Run the script:

bash
 qr_generator

2. Follow the on-screen prompts to enter the text or URL you want to encode into a QR code.

3. Customize QR code settings such as size, color, and error correction level as desired.

4. Once generated, the script will save the QR code as a PNG image in the current directory.

## Examples

python
# Generate a QR code for a URL
generate_qr_code("https://www.example.com")

# Generate a QR code for text with custom settings
generate_qr_code("Hello, world!", size=10, color="black", background="white", error_correction=qrcode.constants.ERROR_CORRECT_H)

## Credits

This project is maintained by [Anurag Rai](https://github.com/anurag87204) and is licensed under the MIT License. 

Feel free to contribute by submitting bug reports, feature requests, or pull requests.

This README.md provides an overview of the project, installation instructions, usage examples, and credits to the project maintainer. Adjustments can be made based on the specific features and details of the project.
