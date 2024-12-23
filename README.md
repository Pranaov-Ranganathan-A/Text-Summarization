# Text Extraction and Summarization

## 1. Text Extraction from Image
   Import the required libraries:
   from PIL import Image
   import pytesseract
   
## 2. Text Summarization
   from transformers import pipeline
   summary = summarizer(extracted_text, max_length=50, min_length=25, do_sample=False)
   print("Summarized Text:", summary[0]['summary_text'])

# Requirements
 Python 3.7+
 Libraries:
 pillow
 pytesseract
 transformers

 # Output
 Extracted Text: The raw text extracted from the image.
 Summarized Text: A summary of the extracted text.
