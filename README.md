# Flask PyMuPDF PDF Text Extractor

This project is a Flask web application that allows users to upload a PDF file and extracts text from it using the PyMuPDF library. The application provides a simple interface for users to interact with and view the extracted text.

## Project Structure

```
flask-pymupdf-app
├── app
│   ├── __init__.py
│   ├── routes.py
│   ├── static
│   │   ├── css
│   │   │   └── styles.css
│   └── templates
│       └── index.html
├── requirements.txt
├── run.py
└── README.md
```

## Installation

1. Clone the repository:

   ```
   git clone <repository-url>
   cd flask-pymupdf-app
   ```

2. Create a virtual environment:

   ```
   python -m venv venv
   ```

3. Activate the virtual environment:

   - On Windows:
     ```
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```
     source venv/bin/activate
     ```

4. Install the required packages:

   ```
   pip install -r requirements.txt
   ```

## Usage

1. Run the application:

   ```
   python run.py
   ```

2. Open your web browser and go to `http://127.0.0.1:5000`.

3. Use the provided form to upload a PDF file. The extracted text will be displayed on the same page after the upload.

## Dependencies

- Flask
- PyMuPDF

## Contributing

Feel free to submit issues or pull requests for improvements or bug fixes.