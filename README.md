# BMP-To-EagleFootprint
BMP to Eagle Library Converter

Overview:
The BMP to Eagle Library Converter is a software tool designed to convert monochrome BMP image files into Eagle library files (.lbr). This converter is particularly useful for creating custom PCB footprints directly from bitmap images, allowing for rapid prototyping and design.

Features:
•	Multiple Unit Support: Convert pad sizes in microns, millimeters, mils, or inches.
•	User-Friendly GUI: Intuitive graphical interface with consistent styling and easy navigation.
•	Flexible Pad Size: Easily adjust pad sizes to fit your design needs.
•	Automatic Scaling: Automatically scales the BMP image to fit within Eagle's coordinate limits.
•	Efficient Pad Generation: Optimized to handle large BMP images with a maximum of 5000 pads.

Technical Specifications:
•	Input: Monochrome BMP files (1-bit per pixel).
•	Output: Eagle library files (.lbr) compatible with Eagle version 9.6.2.
•	Programming Language: Python 3.12.
•	Dependencies:
	tkinter for the GUI.
	Pillow for image processing.

Installation
Prerequisites:
•	Python 3.12 or later.
•	tkinter (usually included with Python).
•	Pillow library:

Usage
1.	Launch the application (open the executable).
2.	Select the BMP file you wish to convert.
3.	Specify the output Eagle library file path.
4.	Enter the desired pad size and select the unit (mic, mm, mil, or inch).
5.	Fill in the library name, package name, symbol name, and device name.
6.	Click "Convert" to generate the Eagle library file.

Limitations
•	BMP Format: Only supports monochrome BMP files (1-bit per pixel).
•	Pad Limit: Maximum of 5000 pads to prevent overwhelming Eagle with excessively large footprints.
•	Scaling: Automatically scales large BMP images, which may result in smaller pad sizes if the image is too large.

Contributing:
Contributions are welcome! Feel free to fork this repository, make improvements, and submit a pull request.

License:
This work is licensed under a Creative Commons Attribution-NoDerivs 4.0 International License.

Copyright (c) 2024, Ian T. Dooley

Contact:
For any questions or support, please open an issue in the repository or contact the maintainer. 
