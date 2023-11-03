# AI-Powered-Startup-Application-Summarizer

## Overview

This project is a prototype of an AI-powered summarization bot that can generate concise summaries of startup applications. The primary use case is to provide investors with a quick and informative overview of a startup application document.

The project is implemented in Python using the Dash web framework for the user interface, the Transformers library for text summarization, and other libraries for document parsing and preprocessing.

## Features

- Upload and summarize startup application documents.
- Preprocess text by removing punctuation and URLs.
- Generate summaries using a pre-trained language model (Facebook's BART).
- Display the summarized text in a user-friendly interface.

## Getting Started

1. Clone this repository to your local machine:

git clone https://github.com/rohith251297/ai-startup-summarizer.git

## Install the required dependencies using pip:

pip install -r requirements.txt

## Run the application:

python app.py

## Open a web browser and navigate to http://localhost:8050 to access the application.

## Usage
1.Click the "Select a Startup Application Document" link or drag and drop a supported document (PDF or DOCX) into the upload area.

2.The application will preprocess the document, generate a summary, and display it in the "Summary" textarea.

## Supported Document Formats
-PDF
-DOCX

## Contributing
We welcome contributions from the community. If you would like to improve this project, please follow these steps:

-Fork the repository.
-Create a new branch for your feature or bug fix.
-Make your changes and ensure the code passes all tests.
-Submit a pull request with a clear description of your changes.

## Acknowledgments
-This project uses the Transformers library for text summarization.
-PDF parsing is done using pdfplumber.
-Word document parsing is done using the python-docx library.
-Stopwords and NLP functionality are provided by the NLTK library.

## Contact
If you have any questions or issues, please feel free to contact Rohith.

































