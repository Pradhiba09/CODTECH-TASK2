
Python-Based Web Vulnerability Scanner

Project Overview

This project aims to develop a simple yet effective Python-based scanner that can detect common web application vulnerabilities, specifically:

                  - SQL Injection (SQLi)
                  - Cross-Site Scripting (XSS)

The tool is built using Python libraries like requests and BeautifulSoup to simulate malicious payloads on URLs and analyze the responses.

Objectives:

- Detect potential SQL Injection points.
- Check for basic XSS vulnerabilities.
- Provide clear output logs to indicate vulnerable parameters.
- Help beginners understand basic web vulnerability scanning techniques.

 Technologies Used:

- Python 3,Requests – for sending HTTP requests,
- BeautifulSoup4 – for parsing and analyzing HTML responses

Working:

1. Takes a target URL with query parameters.
2. Sends various malicious payloads.
3. Analyzes the response to detect:
   - SQL error messages or logic flaws.
   - Reflected XSS scripts in HTML.
4. Displays detected vulnerabilities in a structured format.





