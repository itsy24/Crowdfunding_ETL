![Screenshot 2023-02-23 220655](https://user-images.githubusercontent.com/75823252/221104851-893dafbb-362c-4cca-89bb-cdfb9937f1f0.png)

#Crowdfunding_ETL


## Technologies

For this project we used Python 3.9 and pandas
QuickDBD

---

## Installation Guide

To make sure that the program will work you have to install  python 3.9 and the libraries mentioned above.
QuickDBD https://www.quickdatabasediagrams.com/

---

## Examples
![Crowdfunding_schema_png](https://user-images.githubusercontent.com/75823252/235567068-087c351e-b6c2-45a2-9bee-6b5a8092a413.png)

![Screenshot 2023-05-01 193305](h![Screenshot 2023-05-01 193409](https://user-images.githubusercontent.com/75823252/235567258-b7d8650b-6df3-4e00-8571-61aa6d024bf6.png)
ttps://user-images.githubusercontent.com/75823252/235567253-0ffe26ad-8a06-41f5-888d-781ed3dc8ee9.png)




## Usage
Part 1 - Matheus: To start the project Matheus started importing the libraries and reading the excel file. We analyzed the data and started splitting the column "category & sub-category" in two: "category" and “sub-category". After that we collect the unique values of the two columns to create two new data frames and stored in two new csv files.

Part 2 - Jorge: Started by loading the crowdfunding_info_df into a new data-frame, ‘campaign_df’, in order to clean and rearrange the data. After renaming the columns with their appropriate titles, the ‘goals’ and ‘pledged’ columns’ data types were changed to Floats so that they reflect cent values. Next, ‘launched_date’ and ‘end_date’ columns were formatted by importing ‘datetime’ and using ‘dt.strftime(‘%y-%m-%d’)’ so that the dates show up as YEAR-MONTH-DAY as opposed to the numerical value. ‘Category’ and ‘subcategory’ columns were added by merging ‘category_df’ and ‘subcategory_df’ with ‘campaign_df’ in a new data-frame, ‘campaign_merged_df’, by matching the rows on ‘category’ and ‘subcategory’. Lastly, undated columns were dropped using the ‘.drop’ function and imported the cleaned data-frame to a CSV file.

Part 3 - Rodrigo: For the Contacts DataFrame Rodrigo had to upload a Json file, which was different than the previous excel (csv) files. After  the Json was uploaded he iterated through each row to convert the json rows into a dictionary. Dictionaries are easier to rename, sort and clean the data compared to json files because we can isolate columns to apply functions to, such as ".iloc" and ".astype". Our overall goal for this section was to organize our columns into a more visually friendly Data Frame for readers. We completed option one, in order to finish the project but later got help from rockstar teammates Srabana and Isabel to submit option two as our final submission.

Part 4 - Srabana + Isabel We used the quickdbd to create an erd. exported it and imported into pgadmin to create the tables.


---

## Contributors

Developed for Jorge Dennis, Srabana Guha, Isabel Sy, Rodrigo Zepeda,  Matheus Araujo, using the data provided by UC Berkeley Data Bootcamp.

---

## License

This program is allowed to public use.
