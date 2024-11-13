# Image to STL Converter

## Description
This desktop application converts your image files into 3D-printable layers. Each color is separated into different STL files named by their HEX color, followed by a layer number. Use the HEX code to match the filament color when printing.

> **Note:** As of **11/13**, the layer numbers are reversed. Keep this in mind when stacking your prints or using the PNG files.

## Features
- Upload PNG/JPG images
- Extract up to 10 colors
- Export each color as a separate STL file
- Hex color naming for easy filament matching

## Installation
1. Clone the repo:
   ```bash
   git clone https://github.com/IanStocker02/image-to-stl-converter.git
   cd image-to-stl-converter
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python main.py
   ```

## Requirements
- Python 3.8+
- Tkinter, Pillow, NumPy, scikit-learn, numpy-stl

## Usage
1. **Upload an Image**: Click "Upload Photo".
2. **Adjust Colors**: Use the slider for 2-10 colors.
3. **Convert**: Click "Convert to STL".

## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## Contact
GitHub: [IanStocker02](https://github.com/IanStocker02)  
Email: iant.stocker@gmail.com
