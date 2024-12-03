# PDF-extractor-tkinter


# PDF Text Extractor

## Overview
This is a simple Tkinter-based Python application that allows users to select a PDF file and extract the text content from the first page of the PDF. The extracted text is displayed in a text box within the GUI. The application also includes error handling for missing or non-text PDFs and allows the user to easily browse and select the desired PDF file.

## Features
- **Select a PDF File**: Click the "Browse" button to open a file dialog and choose a PDF file from your system.
- **Extract Text**: The program extracts the text from the first page of the selected PDF file.
- **Display Text**: Extracted text is shown in a text box in the GUI.
- **Error Handling**: Handles missing or non-text PDFs and shows appropriate messages to the user.
- **Scrollable Text Box**: A scrollable text box to view long text content.

## Installation

### Requirements
- Python 3.x
- Tkinter
- Pillow
- PyPDF2

### Installation Steps
1. Clone the repository or download the project files.
2. Install the required libraries:
    ```bash
    pip install PyPDF2 Pillow
    ```

3. Make sure you have the logo image (`logo.png`) in the same directory as your Python script or change the file path in the code accordingly.

4. Run the application:
    ```bash
    python pdf_text_extractor.py
    ```

## Usage
1. When you run the program, a window will appear with an option to browse and select a PDF file from your computer.
2. After selecting the PDF, the application will extract the text from the first page and display it in a text box.
3. If there is no text on the page, a warning message will appear.

