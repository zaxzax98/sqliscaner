# sqliscaner
# SQL Injection Scanner

This project is a tool for scanning websites for SQL Injection vulnerabilities using Google Dorks and the Google Custom Search API.

## Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)

## Introduction

This tool utilizes the `requests` library to make HTTP requests, the `colorama` library to enhance terminal output, and the `marshal` library to obfuscate the code. The aim is to find vulnerable sites and query for SQL Injection vulnerabilities.

## Requirements

Before you begin, ensure you have the following prerequisites:

- Python 3.x
- `requests` library
- `colorama` library
You can install the required libraries using pip:

```bash
pip install requests colorama

Installation
Clone the repository to your local machine:

bash
Copy code
git clone <repository-link>
Navigate to the project directory:

bash
Copy code
cd <folder-name>
Usage
To run the tool, use the following command:

bash
Copy code
python <script-file-name>.py
Follow the prompts to input the dork, the number of results you want, and the domain (if applicable).

Example user input:
mathematica
Copy code
Enter the Google Dork: inurl:index.php?id=
Enter the number of search results: 10
Enter the domain (optional, e.g., iq, il.com, etc.): example.com
License
This project is licensed under the MIT License.

Contributors
[Your Name]
vbnet
Copy code

### How to Use

1. Copy the text above.
2. Open a new text editor.
3. Paste the text into it and save the file as `README.md` in your project folder.
4. Modify the parts that need customization, such as the repository link, script file name, and contributor names.

If you need any changes or additions, feel free to let me know!






