# PDF Resizer

## Description

A simple web application to resize PDF files using Ghostscript. Users can upload PDF files, choose an optimization level, and download the optimized files.

## Installation

1. **Install Ghostscript:**

   This application requires Ghostscript to be installed on the server. Please follow the installation instructions for your operating system.

2. **Clone the repository:**

   ```bash
   git clone https://github.com/nicthegreatest/pdf-resizer.git
   cd pdf-resize
   ```

3. **Install Python dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Run the Flask application:**

   ```bash
   python app.py
   ```

2. **Open the web interface:**

   Open your web browser and navigate to `http://127.0.0.1:5000`.

3. **Upload and optimize:**

   - Drag and drop your PDF files onto the page or click to select them.
   - Choose an optimization level from the dropdown menu.
   - Click the "Optimize" button.

4. **Download the resized files:**

   The resized files will appear in a table. Click the "Download" button to save them.
