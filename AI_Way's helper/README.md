# AI_Way's Helper GPT for Telegram Donate Bot Data Analysis

AI_Way's Helper is a specialized GPT designed for a specific client to automate the conversion of chat message exports from the Telegram Donate bot into structured, tax-ready data tables. This tool uniquely caters to the client's need to efficiently process financial transactions recorded via Telegram, converting them into an organized format suitable for financial analysis and tax reporting.

## Overview

This GPT leverages a custom Python script, `Parser.py`, to parse and analyze JSON exports of chat histories with the Telegram Donate bot. It's tailored to extract, transform, and load data into structured Excel spreadsheets, segmenting financial transactions by quarters for easy tax preparation and analysis. This GPT has Data Analysis mode enabled, allowing it to run Python code in its built-in Jupyter notebook environment.

## Key Features

- **Automated Parsing**: Directly processes `result.json` exports from the Telegram Donate bot, handling large datasets efficiently.
- **Excel Spreadsheet Generation**: Outputs detailed Excel files with transactions categorized by quarter, including date, amount, user information, and payment type (donation, subscription, etc.).
- **Tax Calculation Support**: Facilitates tax reporting by organizing transactions in a way that simplifies the calculation of taxes due, distinguishing between different types of payments.
- **Custom Python Scripting**: Utilizes a bespoke Python script, `Parser.py`, embedded within the GPT to parse and analyze the exported data.

## Implementation

The GPT works exclusively with JSON files obtained from the Telegram Donate bot, requiring the `Parser.py` script to be uploaded to the GPT's file system. It executes predefined Python code blocks to run `Parser.py`, transforming the JSON data into structured Excel outputs without user intervention in the code execution process.

### How It Works

1. **Data Export**: The user exports chat history with the Telegram Donate bot as a JSON file.
2. **Upload and Execute**: The JSON file is uploaded to the GPT, and the embedded Python script (`Parser.py`) is executed to process the data.
3. **Download Results**: The user receives Excel files segmented by quarter, along with summaries of transactions for easy review and analysis.

## How it looks
![First](https://i.imgur.com/V8D9K2d.jpg)
![Second](https://i.imgur.com/hDkjuJM.jpg)
![Third](https://i.imgur.com/Y4bwRC3.jpg)
