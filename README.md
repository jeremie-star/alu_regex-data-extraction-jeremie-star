# Regex Data Extraction Project

## Overview
This project extracts specific types of data from large text files using Regular Expressions (Regex) in Python. It can identify and extract:
- **Email Addresses**
- **URLs**
- **Phone Numbers**
- **Credit Card Numbers**

## Technologies Used
- Python 3.x
- Regular Expressions (`re` module)

## Setup Instructions
1. **Clone the Repository**
git clone https://github.com/jeremie-star/alu_regex-data-extraction-jeremie-star.git

markdown
Copy
Edit
2. **Navigate into the Project Folder**
cd alu_regex-data-extraction-jeremie-star

markdown
Copy
Edit
3. **Ensure Python is Installed**
python --version

markdown
Copy
Edit
4. **Prepare a Sample Input File**
- Create a file named `sample_text.txt`
- Add some test data (emails, URLs, phone numbers, and credit cards)

5. **Run the Script**
python extract_data.py

shell
Copy
Edit

## Example Output
Emails: user@example.com test.email@domain.co.uk

URLs: https://www.example.com https://subdomain.example.org/page

Phone Numbers: (123) 456-7890 123-456-7890

Credit Card Numbers: 1234-5678-9012-3456 1234 5678 9012 3456

markdown
Copy
Edit

## Edge Case Handling
- Supports different email formats (`user+tag@domain.com`)
- Recognizes URLs with or without `www`
- Handles various phone number formats (`(123) 456-7890`, `123.456.7890`)
- Allows credit card numbers with `-` or spaces

