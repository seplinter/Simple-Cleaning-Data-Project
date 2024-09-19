# Data Cleaning and Contact Management

## Project Overview
This project involves cleaning a dataset that includes customer contact information. The main objective is to ensure the dataset is suitable for further analysis or integration into a CRM system by:
- Cleaning and standardizing phone numbers.
- Removing customers who have opted not to be contacted.
- Handling missing and invalid entries.

## Features
1. **Phone Number Cleaning**: 
   - Removes any non-alphanumeric characters.
   - Formats phone numbers into a standardized format (e.g., `XXX-XXX-XXXX`).
   
2. **Do Not Contact Handling**:
   - Filters out customers who opted not to be contacted (`Do_Not_Contact` column with value 'Y').

3. **Missing Values**:
   - Removes rows where crucial fields, such as `Phone_Number`, are missing.
   
4. **Address Parsing**:
   - Splits addresses into `Street_Address`, `State`, and `Zip_Code`.

5. **Export**:
   - The cleaned data is exported to an Excel file (`cleaned_data.xlsx`).

## Technologies Used
- **Python**: Core language for scripting.
- **Pandas**: Library for data manipulation.
- **NumPy**: For handling missing values.
- **openpyxl**: Used for exporting data to an Excel file.

## How to Run the Project
1. Clone the repository:
    ```bash
    git clone https://github.com/seplinter/Simple-Cleaning-Data-Project.git
    ```
2. Navigate to the project directory:
    ```bash
    cd your-repository
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the notebook:
   Open `clean_data.ipynb` in a Jupyter environment and execute the cells.

## Files Included
- **clean_data.ipynb**: Jupyter notebook for data cleaning.
- **Customer Call List.xlsx**: Raw data.
- **cleaned_data.xlsx**: Output file with cleaned data.
- **README.md**: Project documentation.
