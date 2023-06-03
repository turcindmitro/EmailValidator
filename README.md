# CSV to JSON Email Validator

This Python script is a utility that takes a CSV file as input, converts it into a JSON format, and extracts and validates email addresses found in the dataset. 

## Features
- Reads a CSV file and converts it to a JSON file.
- Loads the created JSON file and extracts email addresses.
- Validates the email addresses using a regex pattern.
- Prints valid email addresses.

## Dependencies
- Python 3.6 or higher
- No external dependencies or libraries are required.

## Usage

1. Ensure your CSV file is in the correct format. The script expects a CSV file with a column labeled 'email' which contains the email addresses.

2. Modify the csvFilePath and jsonFilePath variables in the script to point towards your CSV input file and desired JSON output file respectively.
    python
    csvFilePath = r'path_to_your_file.csv'
    jsonFilePath = r'path_to_output_file.json'
    

3. Run the script in a Python environment.
    bash
    python script_name.py
    

The script will convert your CSV file to a JSON file, extract the emails, validate them and print the valid emails in the console.

## Note
The email validation is based on a simple regex pattern which might not cover all the possible email formats, but it is sufficient for most common formats.