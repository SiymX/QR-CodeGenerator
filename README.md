
![qrgenGIT](https://github.com/SiymX/QR-CodeGenerator/assets/63435885/96c298e2-ef86-49c2-8f62-cfcc70683693)

# QR-CodeGenerator
This Program is a Python-based QR Code Generator which does not rely on the `import qrcode` library but uses the QR Server API via the `requests` library to send the request and retrieve the QR Code Data. It allows users to create a QR Code based on the provided URL from the user-friendly Graphical User Interface (GUI) via the `Tkinter` library and the `PIL` library for Image Manipulation.



# Table of Contents
1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Dependencies](#dependencies)





# Features
* **QR Code Generation**: The program generates the QR Codes based on the user-provided URLs. It will then use the QR Server API to get the data and then generate the QR Codes in a high quality image.
* **Logo Customaization**: The users can add a personalized logo to the generated QR Codes which will be positioned at the center of the QR Code for a Unique Appearance.
* **User-Friendly Interface**: The program features a beautiful easy-to-use interface. All the users have to do is enter the URL in a dedicated input field and then generate the QR codes with a singe click.





# Installation
Contributions to this QR Code Generator are welcome. If you encounter any issues then you are welcome to submit a pull request or open an issue. You can also dowload or clone the repostory to your device by using:
```
git https://github.com/SiymX/QR-CodeGenerator.git
```
1. Make sure you have Python installed on your system. You can download the latest version of Python from the official Python Website: https://www.python.org/downloads/. You can also use PyCharm as the development enviornment for this project, download it here from: https://www.jetbrains.com/pycharm/.
2. Install the required dependcies by running the following command:
```
pip install pillow
pip install requests
```
3. Import the following from the library
```
import tkinter as tk
import tkinter.messagebox as messagebox
from PIL import Image, ImageTk
import requests
from io import BytesIO
```





# Usage
You can either run the program via Terminal or run the `exe` file located in the `/dist` folder if you are using an Windows Device. To run it on terminal do the following:
1. Open terminal and navigate to the directory where the program files are located.
2. Run the following command to start the QRCode Generator:
```
python QRCode.py
```
3. The GUI Window of the QR Code Generator will appear.
4. Click the **Generate QR Code** button for image generation.
5. The Image will display on the output label.



# Dependencies
* `tkinter`: For creating the GUI.
* `PIL`: For image processing and displaying the background.
* `requests`: For making HTTP requests to retrieve word explanations.
* `io`: For input/output handling for the binary data.
