# EDGAR Financial Data Parser

## Objective
This project focuses on developing a robust parser for extracting and analyzing financial data from SEC's EDGAR database. The primary objective is to systematically extract quarterly EPS (Earnings Per Share) from 8-K filings in various formats and present the data in a structured and accessible manner. 

## Dependencies
List of dependencies used in this project
1. `python 3.12`
2. `pandas 2.1.4`

## Installation

1. Create a virtual environment
   ```sh
   py -3.12 -m venv .venv
   ```

2. Enter the newly created virtual environment
   ```sh
   .venv\Scripts\activate
   ```

3. Install all the dependencies in the requirements.txt
   ```sh
   py -m pip install -r requirements.txt
   ```

## Usage
1. Go to the Jupyter notebook file [main.ipynb](main.ipynb) and follow the instructions in the file
2. After running the `main.ipynb`, the results will be generated in the CSV file [results.csv](results.csv)