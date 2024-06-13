# CSV-to-JSON-Converter-Using-Python

Welcome to CSV-to-JSON-Converter-Using-Python, this Python script converts CSV (Comma-Separated Values) files to JSON (JavaScript Object Notation) files. It's designed for basic conversion and assumes well-formatted CSV files.

**Project Overview**

CSV-to-JSON-Converter-Using-Python enables you to convert CSV files, commonly used for tabular data, into JSON format. This conversion allows for better data management, analysis, and sharing.

**Features**

1. Exception Handling: CSV-to-JSON-Converter-Using-Python incorporates robust exception handling to ensure smooth data conversion.

2. Converts CSV data into a JSON object structure.

3. Handles basic CSV formatting, including headers as the first row.

4. Outputs the converted JSON data to a new file.

**How to Use** 

1. Create a virtal enviornment and activate it.

2. Install all the prereqesites from requirements.txt.

3. Declare 2 enviornment variables as follows:
    (Windows)
    ```js
    $Env:SRC_BASE_DIR = 'data/retail_db'
    $Env:TGT_BASE_DIR = 'data/retail_db_json'
    ```
4. Run app.py as per requirements

**Use Case**

This would convert all the csv files present in data/retail_db to json
```js
    python app.py
```

To convert files specefic to dataset
```js
    python app.py '[\"orders\" ,\"department\", \"order_items\"]'
```