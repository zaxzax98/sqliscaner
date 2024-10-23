# SQL Injection Scanner

This project is a tool for scanning websites for SQL Injection vulnerabilities using Google Dorks and the Google Custom Search API.

## Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributors](#contributors)

## Introduction

This tool utilizes the `requests` library to make HTTP requests, the `colorama` library to enhance terminal output, and the `marshal` library to obfuscate the code. The aim is to find vulnerable sites and query for SQL Injection vulnerabilities.

## Requirements

Before you begin, ensure you have the following prerequisites:

- Python 3.x
- `requests` library
- `colorama` library
- `marshal` library

You can install the required libraries using pip:


pip install requests colorama

## Installation
Clone the repository to your local machine:


git clone <repository-link>
Navigate to the project directory:

cd <folder-name>
## Usage

To run the tool, use the following command:

```bash
python <script-file-name>.py
```

Follow the prompts to input the dork, the number of results you want, and the domain (if applicable).

### Example user input:

```
Enter the Google Dork: inurl:index.php?id=
Enter the number of search results: 10
Enter the domain (optional, e.g., iq, il.com, etc.): example.com
```

## Contributors
zano_security 

