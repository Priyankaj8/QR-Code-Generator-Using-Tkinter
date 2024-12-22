# QR Code Generator Using Tkinter

This is a simple QR Code Generator application built using Python's Tkinter library for the GUI and the `pyqrcode` library for generating QR codes. The application allows users to input a name and a link, and it generates a corresponding QR code, which is displayed in the window.

## Features
- Input a name for the QR code.
- Input a link for which the QR code will be generated.
- The QR code is generated and displayed in the window.

## Libraries Used
- **Tkinter**: A built-in Python library used for creating the GUI.
- **pyqrcode**: A Python library used to generate the QR code.
- **Pillow (PIL)**: A Python Imaging Library used to handle and display the generated QR code image.

## Requirements
Make sure you have the following libraries installed:
- `pyqrcode`
- `Pillow`

You can install these libraries using pip:

```bash
pip install pyqrcode pillow
```

## Usage
1. Run the script:
   ```bash
   python main.py
   ```

2. The window will open with fields to enter a link name and link. Enter the details and click the "Generate QR code" button.

3. The generated QR code will be displayed in the window.

## Example
1. Enter the link name, e.g., `MyWebsite`.
2. Enter the link, e.g., `https://www.example.com`.
3. Click "Generate QR code" to see the QR code displayed.
4. 
## Screenshots
QR Code Generator Window:  
![4](https://github.com/user-attachments/assets/e7593e6b-98ab-4475-9145-50b09f889847)

How it works:  
![3](https://github.com/user-attachments/assets/ecead929-f387-4340-974c-23776857b4fb)

Generated QR code is saved in the .png format:  
![google](https://github.com/user-attachments/assets/ab7b8700-6c05-4954-b498-7339453117d4)

## Troubleshooting
- If you encounter an error like `ModuleNotFoundError: No module named 'png'`, install the missing package using:
  ```bash
  pip install pypng
  ```
