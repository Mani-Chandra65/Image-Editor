# Image Editor using Pillow

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)  
[![Python Version](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)

A **GUI-based image editor** built with **Python**, leveraging **Tkinter** for the graphical interface and **Pillow** for robust image processing. This project provides a user-friendly tool for performing essential image editing operations, and it’s designed with modularity and scalability in mind.

---

## Table of Contents
- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [Future Enhancements](#future-enhancements)
- [License](#license)

---

## Features

- **Image Manipulation:**  
  - **Open/Save Images:** Easily load and export images in multiple formats (PNG, JPG, etc.).  
  - **Resize & Crop:** Adjust image dimensions with aspect ratio preservation and select specific regions for cropping using a dynamic overlay.
  - **Rotate & Flip:** Rotate images by 90° increments or flip horizontally with a single click.
  - **Filters & Enhancements:** Apply custom filters such as grayscale, blur, and sharpen. Experiment with effects like "Sunny" and "Natural" for color and contrast adjustments.
  
- **User Experience:**  
  - **Intuitive GUI:** A sleek, modern interface built with Tkinter ensures ease of use and immediate visual feedback.
  - **Undo/Redo Functionality:** Robust history tracking enables users to revert changes or redo modifications, promoting creative experimentation.
  - **Real-Time Updates:** Changes are reflected immediately, ensuring a seamless editing experience.

---

## Demo

<img src="./images/demo.png" alt="Screenshot of the Image Editor" width="600"/>

*Screenshot showcasing the user-friendly interface and real-time image editing capabilities.*

---

## Installation

### Prerequisites
- **Python 3.x**: [Download Python](https://www.python.org/downloads/)
- **Pillow Library**: Install via pip:
  ```bash
  pip install pillow
  ```
- **Tkinter**: Typically comes pre-installed with Python on most platforms.

### Clone the Repository
```bash
git clone https://github.com/Mani-Chandra65/Image-Editor.git
cd Image-Editor
```

---

## Usage

Launch the application by running:
```bash
python main.py
```
Use the sidebar buttons to load an image, apply various edits, and save your final output. The intuitive design ensures you can experiment and create without hassle.

---

## Code Structure

- **main.py**: Initializes the GUI, binds event handlers, and manages the main application loop.
- **editor.py**: Contains core image processing functions such as resizing, cropping, rotating, and filtering.
- **utils.py**: Houses utility functions for file handling, history management (undo/redo), and UI customization.
- **assets/**: Contains additional resources such as icons, images, and style guides.

---

## Future Enhancements

- **Advanced Filters & Effects:** Integration of more sophisticated filters, including AI-based enhancements.
- **Batch Processing:** Allow users to edit multiple images simultaneously.
- **Cloud Integration:** Save and load images from cloud storage solutions.
- **User Customization:** Enhanced theme options and personalization settings.

---

## License

Distributed under the **MIT License**. See [LICENSE](LICENSE) for more information.

---

*Happy Editing!*  
Feel free to reach out if you have any questions or suggestions.

Y Mani Chandra Reddy(mailto:manichandra842@gmail.com) | Mani-Chandra65(https://github.com/Mani-Chandra65)
