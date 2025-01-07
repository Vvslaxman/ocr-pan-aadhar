# ocr-pan-aadhar
# Advanced OCR System for Aadhaar and PAN Cards

## Overview
Conceptualized an advanced OCR system using Python and OpenCV to accurately extract text from images, focusing on Aadhaar and PAN cards. Implemented image preprocessing techniques and leveraged Tesseract for text recognition, achieving high precision in extracting relevant details such as names, dates of birth, and card numbers. This solution efficiently processes and analyzes images, enhancing data extraction and validation accuracy.
## Note:
This notebook contains code involving algorithms and image processing techniques that can be included in necessary backend system and utilize as of requirement by integrating proper frontend with it !
## Features
- **Image Preprocessing**: Applied grayscale conversion, denoising, and adaptive thresholding for optimal text recognition.
- **Card Type Identification**: Utilized color analysis to differentiate between Aadhaar and PAN cards.
- **Text Extraction**: Employed Tesseract OCR to extract key information including names, dates of birth, card numbers, and other relevant details.

## Dependencies
- Python
- OpenCV
- PIL (Python Imaging Library)
- Tesseract OCR

## Installation
1. Install the required libraries:
    ```bash
    pip install opencv-python pillow pytesseract numpy
    ```
2. Ensure Tesseract OCR is installed and its path is correctly set in the code:
    ```python
    pytesseract.pytesseract.tesseract_cmd = r'C:\Path\To\Tesseract\tesseract.exe'
    ```
3. **Clone the repository:**
    ##### Create a new directory and name a python file as mentioned below 
   ```sh
   git clone https://github.com/yourusername/ocr-pan-aadhar.git
   cd ocr_system.py
   ```
    

## Usage
1. Place your Aadhaar or PAN card image in the specified path.
2. Run the script to extract details:
    ```python
    python ocr_system.py
    ```

## Output
The system differentiates between Aadhaar and PAN card images and extracts their respective details:

For Aadhaar Card :

Type of Card: Aadhaar
Name: ""
Date of Birth: ""
Sex: ""
Aadhaar Number: ""
VID: ""
For PAN Card :

Type of Card: PAN
Name: ""
Father's Name: ""
Date of Birth: ""
PAN Number: ""

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or new features.

### Steps to Contribute:

1. **Fork the repository:**

   ```sh
   git clone https://github.com/yourusername/react-dashboard.git
   cd react-dashboard
   ```

2. **Create a new branch for your feature or bugfix:**

   ```sh
   git checkout -b feature-or-bugfix-name
   ```

3. **Make your changes and commit them:**

   ```sh
   git commit -am 'Add new feature or fix'
   ```

4. **Push your branch to GitHub:**

   ```sh
   git push origin feature-or-bugfix-name
   ```
5. **Create a Pull Request:**
   - Go to the repository on GitHub.
   - Click on the "New Pull Request" button.
   - Provide a description of your changes and submit the PR.

## Acknowledgements

- Special thanks to the developers of [OpenCV](https://opencv.org/) and [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) for providing the essential tools and libraries that made this project possible.
- Gratitude to the contributors of the [PIL (Python Imaging Library)](https://pillow.readthedocs.io/en/stable/) for their excellent imaging library.
- Thanks to the open-source community for providing invaluable resources and documentation.


## Contact

For any questions or suggestions, please open an issue or contact [Vvslaxman](mailto:vvslaxman14@gmail.com).
