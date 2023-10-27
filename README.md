# Data Extraction and NLP Assignment

## Overview
This repository contains the code for an assignment that involves data extraction from given URLs and performing text analysis. The objective is to compute various text analysis variables as described in the "Text Analysis.docx" file for a set of articles provided in the "input.xlsx" file.

## Features
- Data extraction from URLs using Python libraries like Beautiful Soup, Selenium, or Scrapy.
- Text analysis to calculate the following variables:
  1. POSITIVE SCORE
  2. NEGATIVE SCORE
  3. POLARITY SCORE
  4. SUBJECTIVITY SCORE
  5. AVG SENTENCE LENGTH
  6. PERCENTAGE OF COMPLEX WORDS
  7. FOG INDEX
  8. AVG NUMBER OF WORDS PER SENTENCE
  9. COMPLEX WORD COUNT
  10. WORD COUNT
  11. SYLLABLE PER WORD
  12. PERSONAL PRONOUNS
  13. AVG WORD LENGTH

## Getting Started
Follow these steps to use the code and replicate the analysis:

1. **Clone this repository:**
   ```bash
   git clone https://github.com/yadav03vishal/data-extraction-nlp-assignment.git
Install the required Python libraries if not already installed: pip install pandas requests beautifulsoup4 nltk textblob
Download NLTK data for stopwords and tokenization:
import nltk
nltk.download('stopwords')
nltk.download('punkt')
Run the Python script: Perform data extraction and analysis. The script is located in the root directory and named data_extraction_nlp.py.

Output: The extracted text and calculated variables will be saved in the article_texts directory, and an output Excel file named Final_Answer.xlsx.

File Structure
The repository includes the following files and directories:

data_extraction_nlp.py: The Python script for data extraction and text analysis.
input.xlsx: Input data containing URLs and corresponding URL IDs.
article_texts/: Directory to save extracted article text files.
Final_Answer.xlsx: Output file with the calculated variables.
README.md: This readme file.
License
This project is released under the MIT License, which means you can use, modify, and distribute the code as long as you include the original license text.

Acknowledgments
Python community for creating and maintaining the libraries used in this assignment.
Your instructor or course for providing the assignment and data.
Feel free to reach out if you have any questions or need further assistance with the code.



