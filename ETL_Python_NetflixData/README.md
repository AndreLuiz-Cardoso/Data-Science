# ETL Process with Python

This repository contains a project for Extract, Transform, Load (ETL) of data using Python. The goal of this project is to perform data processing and treatment efficiently and reliably.

## Virtual Environment

To ensure an isolated and consistent development environment, a virtual environment was created using Python's `venv` library. This allows the project to be executed with its own dependencies without interfering with the global Python environment.

## Project Structure

The project is organized into two main folders:

1. **data/raw**: Contains the raw data to be processed. This data is extracted from external sources and may be in different formats and states.
2. **data/ready**: Stores the processed data ready for use in analysis or other applications. This folder contains the data after being treated and transformed during the ETL process.

## Data Processing Steps

The ETL process follows these steps:

1. **Extraction**: Data is extracted from the files in the `data/raw` folder.
2. **Transformation**: Raw data is processed and transformed as necessary to meet project requirements. This includes cleaning, filtering, and data type conversion, among others.
3. **Error Identification**: A step was created to identify possible errors in the data, aiming to treat them properly before transformation.
4. **Load**: Processed data is saved in the `data/ready` folder for further analysis or use.

## Technologies Used

- **Python**: Primary programming language used in the project.
- **Pandas**: Data analysis library that provides data structures and tools for data manipulation and analysis.
- **Openpyxl**: Library used to read and write Excel files, ensuring integration with different data sources.
- **XlsxWriter**: Library used to write data to Excel files.

## Database

The information used in this project was extracted from Netflix platform users.

## Data Stages

- **Data Raw**: All data before any polishing or processing, it's the data in its rawest form.
- **Data Ready**: When the data has gone through its refinement process.

This project aims to ensure data reliability and traceability, providing a solid foundation for future analysis and informed decision-making.
