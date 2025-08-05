# Python Excel Reader 

This Python script reads an Excel workbook, applies a 10% discount to prices listed in column 3 (C), writes the corrected prices into column 4 (D), and generates a bar chart based on the corrected prices.

## Features

- Loads a given `.xlsx` file.
- Applies a 10% discount to values in column 3 (assumed to be the original prices).
- Writes the discounted values to column 4.
- Inserts a bar chart using the discounted prices.
- Saves the updated file.

## Requirements

- Python 3.x
- openpyxl

## Installation

Install the required package using pip:

```bash
pip install openpyxl
