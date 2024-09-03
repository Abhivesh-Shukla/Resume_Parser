# Resume Parser

This Python project extracts and processes information from resumes in PDF format. The script uses `pdfminer` for text extraction and regular expressions to identify and extract key details such as name, contact number, email, skills, education, and work experience.

## Features

- **Text Extraction**: Extracts raw text from PDF files.
- **Name Extraction**: Identifies and extracts the candidate's name from the resume.
- **Contact Number Extraction**: Extracts contact numbers, supporting various formats.
- **Email Extraction**: Identifies and extracts the candidate's email address.
- **Skills Section Identification**: Detects and extracts the skills section from the resume.
- **Education Extraction**: Identifies and extracts educational qualifications.
- **Experience Extraction**: Extracts work experience and relevant sections from the resume.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Abhivesh-Shukla/Resume-Parser.git
    cd resume-parser
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

    Ensure the following libraries are included in `requirements.txt`:

    ```text
    pdfminer.six
    scikit-learn
    ```

## Usage

1. Place the PDF resume in the project directory.

2. Update the `pdf_path` variable in the script with the path to your PDF file:

    ```python
    pdf_path = "/path/to/your/resume.pdf"
    ```

3. Run the script:

    ```bash
    python resume_parser.py
    ```

4. The script will output extracted information such as the candidate's name, contact details, skills, education, and experience.

## Example

```bash
Resume: /path/to/your/resume.pdf
Name: John Doe
Contact Number: (123) 456-7890
Email: johndoe@example.com
Skills: 
- Programming Languages: Python, Java, C++
- Tools / Libraries: TensorFlow, Scikit-learn, Pandas

Education: 
- Bachelor of Science in Computer Science
- Master of Science in Artificial Intelligence

Experience: 
- Software Engineer at TechCorp
- Data Scientist at DataSolutions
  ```
## Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss improvements or fixes.


