# Snowflake Requirements.txt Demo

This repository demonstrates Snowflake's ability to automatically install packages from requirements.txt files, including non-Anaconda packages via external access integration.

## What This Demonstrates

- **Automatic Package Installation**: Install packages from requirements.txt using `!pip install -r requirements.txt`
- **External Access Integration**: Access PyPI packages that aren't in the Anaconda channel
- **Non-Anaconda Packages**: Install packages like requests, beautifulsoup4, plotly, fastapi, etc.
- **Standard Pip Workflows**: Use familiar Python package management in Snowflake

## Repository Contents

- `requirements-demo.ipynb`: Jupyter notebook demonstrating package installation
- `requirements.txt`: Package specification file with non-Anaconda packages
- `README.md`: This documentation

## Prerequisites

- Snowflake account with external access integration enabled
- Container runtime notebooks (for full pip support)
- External access integration for PyPI

## Usage

1. Clone this repository in Snowflake
2. Open the notebook in Snowflake Notebooks
3. Run the cells to see automatic package installation
4. Verify that all packages work correctly

## Key Benefits

- **No Manual Setup**: Packages install automatically from requirements.txt
- **Reproducible Environments**: Same packages across all users
- **Standard Workflows**: Use familiar pip commands
- **External Access**: Install any PyPI package
- **Team Collaboration**: Share exact environment specifications

## Packages Demonstrated

- **Web Scraping**: requests, beautifulsoup4, lxml
- **Data Processing**: openpyxl, pandas
- **Visualization**: plotly, dash
- **Web Frameworks**: fastapi, streamlit
- **Data Validation**: pydantic
- **Server**: uvicorn

This demonstrates that Snowflake can handle any Python package, not just those in the Anaconda channel.
