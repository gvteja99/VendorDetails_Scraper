
# PMSVANidhi Portal Scraper for Street Vendor Details

The PMSVANidhi Portal, developed by SIDBI in collaboration with MoHUA, serves as a digital platform for street vendors to apply for benefits under the PMSVANidhi Scheme. It provides guidelines and facilitates loan applications, emphasizing user data protection and responsibility. However, it doesn't guarantee loan approvals, which are at the lenders' discretion.

This script (`vendor_list.py`) automates the process of scraping the complete details of street vendors from selected Urban Local Bodies (ULBs) using Selenium.

## Requirements:

- Python
- Selenium
- ChromeDriverManager
- tqdm (for progress bars)
- pandas

## Installation:

1. **Setup**:
    - Ensure you have the necessary libraries installed:
      ```
      pip install selenium webdriver_manager tqdm pandas
      ```

## How to Use:

1. **Run the Script**:
    - Execute the script using:
      ```
      python vendor_list.py
      ```

2. **Output**:
    - Once the script completes its execution, it will save the scraped data in a CSV file named `vendor_list.csv`.

## Features:

- The script targets the website [https://pmsvanidhi.mohua.gov.in/Schemes/SearchVendor](https://pmsvanidhi.mohua.gov.in/Schemes/SearchVendor).
- It is set to scrape data for the state of GUJARAT.
- The ULB covered in this script are: 'Ahmedabad'. You can also give a list of ULBs to scrape. 
- The details extracted include: SRN No, SV Name, Father’s Name/Spouse Name, ULB Name, Gender, Age, and DOB.

## Precautions:

- Ensure you have a stable internet connection.
- Do not manually interrupt the browser while the script is running.

## Permissions and Legalities:

- According to the website's `robots.txt`, scraping isn't disallowed and the script waits 10 seconds before requesting new information.
- Additionally, nothing is stated in the website's Terms & Conditions, Privacy Policy, and Disclaimer regarding restrictions against web scraping. 

However, always remember:
- It is essential to review and respect a website's `robots.txt` file, terms of service, and other legal documents regularly, as they may change over time.
- Ensure you are compliant with all local, state, national, and international regulations when scraping and using the data.

