# sqliscaner
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

```bash
pip install requests colorama
