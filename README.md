# rc-inshorts-creator

**Weekly-Inshorts-Creator**

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Files Description](#files-description)

## Introduction
The `rc-inshorts-creator` is a tool designed to automate the generation of weekly inshorts reports. It processes data from Excel files and converts it into a visual summary.

## Features
- Generate HTML tables from Excel data.
- Provide category-wise and family-wise counts.
- Shell script for weekly inshorts creation.

## Installation
### Prerequisites
- Python 
- pandas
- openpyxl

### Steps
1. Clone the repository:
    ```sh
    git clone https://github.com/.../.../rc-inshorts-creator.git
    cd rc-inshorts-creator
    ```
2. Install the required libraries:
    ```sh
    pip install -r requirements.txt
    ```

## Usage
1. **Running the Script**:
    - To generate the HTML table from the Excel file, run:
        ```sh
        python excel_to_html.py
        ```
    - To create weekly inshorts, use the shell script:
        ```sh
        ./weekly_inshorts_creator.sh
        ```

## Files Description
- `category_wise_count.txt`: Contains category-wise counts of "".
- `excel_to_html.py`: Python script to convert Excel data to HTML table.
- `family_wise_count.txt`: Contains family-wise counts of "".
- `inshorts-table.xlsx`: The source Excel file containing the data.
- `requirements.txt`: List of Python dependencies.
- `weekly_inshorts_creator.sh`: Shell script to automate the creation of weekly inshorts.

