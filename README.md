# cv-information-extractor
 This script extracts name, email, phone number, and text from PDF or DOCX resumes, saving them in an Excel file for analysis.
 This script extracts information such as name, email, phone number, and text from resumes (CVs) provided in PDF or DOCX format. It then stores this information in an Excel file for further analysis.

## Features

 - Extracts text from PDF and DOCX files.
 - Uses regular expressions to extract emails and phone numbers from the extracted text.
 - Creates an Excel file containing extracted information for each CV processed.

## How to Use

 1. Clone this repository to your local machine:

 2. Install the required dependencies. Make sure you have Python installed on your system.

 3. Ensure that your CV files are stored in a directory named "Sample2" within the project directory.

 4. Run the script

 5. After execution, you will find the extracted information stored in a file named `cv_info.xlsx` in the project directory.

## Dependencies

 - PyPDF2
 - python-docx
 - openpyxl
