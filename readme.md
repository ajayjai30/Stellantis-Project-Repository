# Stellantis Automated Parameter Comparison Tool

## Description

This project is a part of the competition conducted by stellantis, In this project we automated the extraction and comparison of structured parameters from multiple documents. Users can upload two or more documents in various formats, and the tool extracts key parameters using natural language processing (NLP) and regex techniques. It then compares these parameters side-by-side, highlighting matches and mismatches with confidence scores.

## Features

- Supports multiple document formats: PDF, DOCX, XLSX, and XML.
- Extracts structured parameters using SpaCy NLP and regex fallback.
- Compares parameters across documents with confidence scoring.
- Highlights mismatches for easy identification.
- Customizable dark mode for better user experience.
- Download comparison results as CSV.

## Installation

1. Clone or download this repository.
2. Ensure you have Python 3.7 or higher installed.
3. Install the required dependencies using pip:
   ```
   pip install -r requirements.txt
   ```

## Usage

Run the Streamlit app with the following command:

```
streamlit run Main.py
```

This will launch the web interface in your default browser.

### How to use the app:

- Upload two or more documents in supported formats (PDF, DOCX, XLSX, XML).
- The app will extract parameters and display a side-by-side comparison table.
- Use the sidebar filters to show all parameters or only mismatches.
- Search for specific parameters using the search box.
- Download the comparison results as a CSV file.

## Supported File Formats

- PDF (.pdf)
- Microsoft Word (.docx)
- Microsoft Excel (.xlsx)
- XML (.xml)

## Dependencies

- pandas
- openpyxl
- PyMuPDF
- python-docx
- spacy
- streamlit

## License

This project is provided as-is without any explicit license.
