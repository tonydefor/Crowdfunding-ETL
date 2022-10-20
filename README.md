# Crowdfunding-ETL

## Overview

In this Challenge, we used Python, Pandas, and Jupyter notebooks to do the extract and transform phases. Specifically, we extracted and transformed the backers’ contact information from a CSV file to create a DataFrame that will be exported as a CSV file.  Then, completed load phase. Specifically, we used the dataset to create an ERD and a table schema for creating a new table in the crowdfunding_db database. We then uploaded the CSV file that contains the backers’ information into this table. Finally, performed a data analysis on the crowdfunding_db database by using SQL queries.

### Crowdfunding Schema
![crowdfunding_db_schema](https://user-images.githubusercontent.com/47859209/196857645-7647950c-7de7-454f-97cb-8792bdb5675b.png)

### Reordered our backers table and split the names column into first and last names
![reordered_backers](https://user-images.githubusercontent.com/47859209/196858048-b74c1d8c-74aa-45f8-aa97-64aac9e36693.png)

### Wrote an SQL Query table and named it email contacts
![email_contacts](https://user-images.githubusercontent.com/47859209/196858329-0d148620-fcae-4f5f-971f-3e3a318a2e6f.png)


### Wrote another SQL Query table and named it email backers, containing email addresses of the backers in descending order, the first and the last name of each backer, the cf_id, the company name, the description, the end date of the campaign, and the remaining amount of the campaign goal as "Left of Goal".
![email_backers](https://user-images.githubusercontent.com/47859209/196858889-cff353e5-5e1d-407d-a80a-e86320cab99b.png)


## Conclusion
- We were able to assist Independent Funding and Britta with the help they needed by completing the ETL process 
