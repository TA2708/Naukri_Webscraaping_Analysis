# Naukri Job Scraper  

## Overview  
This project is a web scraping tool that extracts job listings from [Naukri.com](https://www.naukri.com/). It automates job searches for different roles and locations using **Selenium**, 
cleans the collected data using **Pandas**, and finally visualizes the results in **Power BI**.  

## Features  
- **Automated Job Search**: Scrapes job listings for roles such as *Data Analyst, Data Scientist, and Data Engineer* in multiple cities.  
- **Data Extraction**: Captures job title, company name, experience required, location, rating, and salary.  
- **Pagination Handling**: Iterates through multiple job listing pages for comprehensive data collection.  
- **Data Cleaning & Storage**: Saves structured data into CSV files.  
- **Visualization**: The cleaned data is analyzed and visualized in Power BI for insights.  

## Requirements  
Ensure you have the following dependencies installed:  

```bash
pip install selenium pandas numpy webdriver-manager
```

Also, download the [Chrome WebDriver](https://sites.google.com/chromium.org/driver/) and update the `chrome_driver_path` variable in the script accordingly.  

## Usage  

1. **Run the script**  
   - Execute the Python script using Jupyter Notebook or any Python environment.  

2. **Scraping Process**  
   - The script opens Naukri.com, inputs job roles and locations, and scrapes job listings dynamically.  

3. **Data Cleaning & Storage**  
   - The extracted data is stored in CSV files.  

4. **Power BI Visualization**  
   - Import the CSV file into Power BI for data analysis and visualization.  

## Output  
- Individual CSV files for each job role and city.  
- A merged CSV file `All_Jobs.csv` containing all the collected job data.  
- Power BI dashboard (if applicable).   

