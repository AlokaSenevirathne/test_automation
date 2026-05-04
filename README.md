# IT3040 – Assignment 1 Test Automation

## Setup Instructions

Install Python (3.11 or above)

Install dependencies:
pip install playwright openpyxl

Install browsers:
python -m playwright install

## How to Run

Run the following command:

python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open

## Description

This project automates the testing of a Singlish to Sinhala translation system using Playwright. It reads test cases from an Excel file, inputs them into the system, and records the results automatically.