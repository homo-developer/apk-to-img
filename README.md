# APK to Image Converter  

This Flask-based web application converts an APK file into an image representation of its `.dex` files.  

## Features  
- Upload an APK file  
- Convert its `.dex` files into a hexadecimal color format  
- Generate a malware visualization image  
- Resize and grayscale the image for better analysis  
- Automatically manage file storage and cleanup

### Prerequisites  
- Python 3.x  
- Pip

Usage

Upload an APK file using the web interface.

The application extracts .dex files, converts them into RGB colors, and generates an image.

Processed images are stored in the images folder.
