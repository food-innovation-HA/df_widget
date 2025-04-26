# Overview for df_widget                                                                                            !!
# Quickly transform .xlsx, .csv, or even memory-stored (i.e., copied) data into a Pandas DataFrame using ipywidgets !!
----------------------------------------------------------------------------------------------------------------------

# df_widget

An interactive data import widget built with Jupyter Notebook and ipywidgets. This project allows you to rapidly load data into a Pandas DataFrame either by uploading a CSV/Excel file or by directly copying and pasting your data. Once the data is loaded, the widget confirms the operation by displaying the DataFrame’s header (column names) and the first five rows.

## Features

- **File Upload:** Easily select a CSV or Excel file to import your data.
- **Copy & Paste:** Directly paste your spreadsheet data into the interface.
- **Data Preview:** Instantly review the loaded data (header and first five rows) to confirm success.

## Installation

**Clone the Repository:**

e.g.```bash
   git clone https://github.com/food-innovation-HA/df_widget.git
   cd df_widget

## Usage
- Open nb_widg_df.ipynb in Jupyter Notebook.
- Choose your data import method using the radio buttons:- File Upload: Select a CSV or Excel file from your system.
- Copy & Paste: Paste your spreadsheet data directly into the provided textarea.

- Once data is provided, the widget will process it and display the DataFrame’s header along with the first five rows to confirm that the data was loaded successfully.

## Requirements
- Python 3.9 or higher
- Jupyter Notebook or JupyterLab
- ipywidgets (v8.1.5 or later)
- pandas

## License
This project is licensed under the MIT License
