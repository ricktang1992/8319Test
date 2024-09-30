#OWASP Dependency Check Tool - ML4Cyber
##Developed by The Tech Titans
  _Mandeep Singh
  _Christopher St.Aubin
  _Ziyao Tang
  _Allan Torres
  _Cyn Vernon
  _Ting Wang
  _Project Overview
This project provides a Python-based application integrated with the OWASP Dependency Check CLI for running security checks on specified directories. The tool generates a report in HTML format that details vulnerabilities in open-source libraries and directories. It is designed to be used by cyber security analysts and IT professionals for better vulnerability management.

This project is a part of the Algonquin College Software Development Project course (CST8334) and has been developed under the guidance of Professor Asim Javaid Butt.

Features
OWASP Dependency Check Integration: Run OWASP security checks on directories or projects.
Report Generation: Generate OWASP dependency check reports in HTML format.
User-Friendly GUI: Visual interface for selecting directories, running checks, and viewing progress.
Error Handling: Displays appropriate error messages for invalid selections or failed checks.
Save Results: Users can save the generated report to their local system.
Requirements
Python 3.x
OWASP Dependency Check CLI
Operating Systems Supported: Windows, Linux, and macOS
Installation
Clone the Repository:

bash
Copy code
git clone https://github.com/your-repo/owasp-dependency-check.git
cd owasp-dependency-check
Install Dependencies:

bash
Copy code
pip install -r requirements.txt
Configure OWASP Dependency Check CLI:
Ensure that the OWASP Dependency Check CLI is installed and accessible from your system's PATH.

Run the Application:

bash
Copy code
python main.py
Usage
Launch the application and select the directory to run the OWASP dependency check.
View progress through the built-in progress bar.
Once complete, the HTML report will be generated and can be saved to your local file system.
Testing
Unit Tests: Ensure the functionality of directory selection and report saving.
Integration Tests: Validate the connection between the GUI and the OWASP Dependency Check CLI.
User Acceptance Tests: Ensure the GUI meets the client’s needs and functions as expected.
Run tests using:

bash
Copy code
python -m unittest
License
This project is licensed under the MIT License - see the LICENSE file for details.
