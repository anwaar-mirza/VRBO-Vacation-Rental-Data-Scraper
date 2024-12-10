# VRBO Vacation Rental Data Scraper

## Overview
The **VRBO Vacation Rental Data Scraper** is a Python-based project that uses web scraping techniques to extract vacation rental data from VRBO. The extracted data includes key details such as property names, descriptions, prices, locations, and amenities. This tool is ideal for data analysis, market research, or building rental property datasets.

## Features
- **Dynamic Pagination Handling:** Automatically navigates through multiple pages of rental listings.
- **Detailed Property Data:** Extracts titles, descriptions, prices, locations, and amenities.
- **Structured Data Output:** Saves the scraped data into a CSV or Excel file for further analysis.
- **Customizable Filters:** Allows adjustments for specific search parameters like location or rental type.

## Requirements
- Python 3.8+
- Required Libraries:
  - `selenium`
  - `beautifulsoup4`
  - `pandas`
  - `undetected_chromedriver` (optional for bypassing detection)

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/vrbo-vacation-rental-scraper.git
   cd vrbo-vacation-rental-scraper
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Open the `vrbo_vacational.ipynb` notebook in Jupyter Notebook or JupyterLab.
2. Update the configuration section in the notebook with desired filters (e.g., location, number of guests, dates).
3. Run all cells to scrape the data.
4. Export the scraped data to CSV or Excel format.

## Output
The output data includes:
- Property Name
- Description
- Price per Night
- Location
- Amenities
- Number of Bedrooms and Bathrooms
- Property Ratings (if available)
- and more available in code

## Notes
- Ensure that you comply with VRBO's terms of service when using this scraper.
- Use responsibly and avoid overloading the website's servers.

## Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue for any improvements or bugs.

## Author
**Anwar Mirza**  
