# Nobel Prize Data Analysis Project

This project includes scripts to fetch, process, and analyze Nobel Prize data. The data is obtained from the Nobel Prize API and processed to extract insightful information about Nobel laureates and prizes.

## Files

### `fetch_nobel_prizes.py` (Code1.txt)

This script is designed to interact with the Nobel Prize API to fetch data about Nobel prizes and laureates. It features functions to retrieve all Nobel Prize data and details about individual laureates. It handles pagination and iterates through the API response to compile a comprehensive dataset.

Key Features:
- Fetch all Nobel Prize data
- Retrieve individual laureate details
- Error handling for API request failures

### `analyze_nobel_prizes.py` (code2.txt)

This script takes the data fetched by `fetch_nobel_prizes.py` and performs data analysis. It processes the data to create a pandas DataFrame, which is then used to analyze various aspects of the Nobel Prize data, such as gender distribution, prize categories, and geographical distribution of laureates.

Key Features:
- Create a pandas DataFrame from fetched data
- Analyze laureate details (gender, birth place, prize category)
- Save processed data to a CSV file for further analysis

## Usage

1. Ensure you have Python 3.x installed along with the required packages (`requests`, `pandas`, `gender_guesser`).
2. Run `fetch_nobel_prizes.py` to fetch the data from the Nobel Prize API.
3. Run `analyze_nobel_prizes.py` to process and analyze the fetched data.
4. The analyzed data will be saved to `nobel_prizes.csv` in the specified directory.

## Requirements

- Python 3.x
- pandas
- requests
- gender_guesser

Please refer to the respective scripts for more detailed information on the functionality and implementation.