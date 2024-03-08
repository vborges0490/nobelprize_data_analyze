# Nobel Prize Data Analysis Project

This project includes scripts to fetch, process, and analyze Nobel Prize data. The data is obtained from the Nobel Prize API and processed to extract insightful information about Nobel laureates and prizes.

## Files

- nobel_prizes.csv - Data Source
- Nobel.ipynb - API Collection
- Nobel_DataAnalyze.ipynb - Data Analyze

### `Nobel.ipynb`

This script is designed to interact with the Nobel Prize API to fetch data about Nobel prizes and laureates. It features functions to retrieve all Nobel Prize data and details about individual laureates. It handles pagination and iterates through the API response to compile a comprehensive dataset.

Key Features:
- Fetch all Nobel Prize data
- Retrieve individual laureate details
- Error handling for API request failures
- Consolidate into CSV for consume.

### `Nobel_DataAnalyze.ipynb`

This script takes the data fetched by `Nobel.ipynb` and performs data analysis. It processes the data to create a pandas DataFrame, which is then used to analyze various aspects of the Nobel Prize data, such as gender distribution, prize categories, and geographical distribution of laureates.

Key Features:
- Create a pandas DataFrame from fetched data
- Analyze laureate details (gender, birth place, prize category)
- Remove data and consolidate necessary columns
- Save processed data to a CSV file for further analysis
- Generate graphs and data analyze

## Usage

1. Ensure you have Python 3.x installed along with the required packages (`requests`, `pandas`, `pyplot`, `plotly`).
2. Run `Nobel.ipynb` to fetch the data from the Nobel Prize API.
3. The analyzed data will be saved to `nobel_prizes.csv` in the specified directory.
4. Update the .env file with the directory to allow run the step 5.
5. Run `Nobel_DataAnalyze.ipynb` to process and analyze the fetched data.

## Requirements

- Python 3.x
- pandas
- requests
- pyplot
- plotly

## Source

- https://www.nobelprize.org/ --- External Data 
- https://www.nobelprize.org/about/developer-zone-2/ --- Public API
- https://unesdoc.unesco.org/ark:/48223/pf0000366803#:~:text=UNESCO%20is%20giving%20special%20attention%20to%20this%20issue,of%20students%20pursuing%20STEM%20fields%20in%20higher%20education. --- UNESCO Study
- https://business.gov.au/grants-and-programs/women-in-stem-and-entrepreneurship --- STEM Program AU

Please refer to the respective scripts for more detailed information on the functionality and implementation.
