## Statista Crawling Project

### 1. crawling.ipynb

- In this notebook, we perform web scraping of the Statista website using Selenium.
- XPATH values are primarily used for complex selections.
- The targets for scraping include chart images, titles, captions, and data files.
- File organization is done using the glob module.

### 2. data_sheet.ipynb

- This notebook downloads data files in xlsx format and removes any unnecessary sheets other than the data sheet.
- It saves the cleaned files with only the relevant data sheet.

### 3. edit.ipynb

- This file handles cases where chart image capture has failed.
- Removal targets include cases where chart images are too long or there are premium charts.
- Removal targets are manually selected and processed using this file.
