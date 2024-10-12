# QR-Code-using-Python
Customized a QR code for my GitHub Profile

This project demonstrates how to generate and customize QR codes using the MyQR library in Python. QR codes are a great way to share information like URLs, text, or even Wi-Fi credentials by encoding the data into a scannable image.

In this project, the following steps are covered:

- Generating a Basic QR Code: A QR code is generated with a link to my GitHub profile.
- Customizing the QR Code: A customized QR code is created by adding a background image and changing the appearance of the code.
- Displaying the QR Codes: The generated QR codes are displayed directly within the Jupyter Notebook for visual verification.

### Steps Involved:
1. Basic QR Code Generation:
- The myqr.run() function is used to generate a basic QR code with the content of a URL.
- In this example, the QR code encodes the URL to my GitHub profile.
- The generated QR code is saved as an image file (yashikahoodaGitHubLink.png).

2. Displaying the Generated QR Code:
The QR code is loaded and displayed using PIL (Python Imaging Library).

3. Customizing the QR Code:
- The myqr.run() function allows adding a background image and making the QR code colorized.
- In this example, the QR code encodes the GitHub URL and incorporates a custom image (picture.png) as the background.
- The customized QR code is saved as my_qr_with_github_background.png

4. Displaying the Customized QR Code:
The customized QR code with the background image is displayed using PIL.

#### Customization Features:
- Background Image: You can add any image to the QR code to make it visually appealing.
- Colorization: You can generate a colorized QR code instead of the default black and white.
This project provides a simple and fun way to generate both basic and custom QR codes for sharing information in a visually attractive manner. The generated QR codes are saved locally and displayed within the Jupyter Notebook, making it easy to verify and share.
