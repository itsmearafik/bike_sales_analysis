# Pivot Tables and Dashboard in Ms Excel

An exploratory analysis on the performance of bike sales

The tasks for this project are:

- clean data.
- analyze  data.
- create a dashboard using Pivot Tables.

This project was made in Ms Excel but can be viewed in Google sheets or Ms Excel.
The final result: ![] (<https://github.com/itsmearafik/bike_sales_analysis/blob/main/Excel_bikesales_Project%20Dataset.xlsx>)

This project covers data cleaning, data analysis and data visualization process using Microsoft excel, and this is the project’s documentation.

The major aim of this project is to communicate insights via an interactive dashboard determining the demographic factors that influences bike purchases. I will be using bicycle buyers’ different demographics to gather my insights and give recommendations.

Steps or Procedures used to complete the above tasks:

## 1. Duplicate the raw data

 > [!TIP] I made a copy of the main (raw) data to prevent any unforseen scenarious of not been able to fall back to the untempered data.

## 2. Begin exploring or profiling the data

     Made use of the conditional formating and the filter option to have a look and understand the data am working with.

## 3. Cleaning the data

    - Removing duplicates: I removed duplicate rows from the raw data as the begining of my data cleaning process.
    - Columns for 'Marital Status' and 'Gender'  used the same letters to represent different meaning of data.
        For clarity, I changed how the data is represented by: replacing 'M' with 'Married' and 'S' with Single in the Marrital Status column.
        I also changed 'M' to 'Male' and 'F' to 'Female' in the Gender column.
    - Column for 'Income' had a some decimal data type entries, so I changed all data points in the 'Income' column to the nearest whole number (integer).
    - Column for 'Commute Distance' to properly enable me to sort or order this data in Pivot tables with ease, I changed the data entries '10+ Miles' to 'More than 10 Miles'.
    - Column for 'Age Brackets': created this new column to contain all the ages in three (3) different groups based on the column for 'Ages' because it represented ages individually, not as a range.
    > i.e Adolescents - < 31 <br>
          Middle Age - 31 to 54 <br>
          Old - > 55

## 4. Pivot Table

- I created three (3) different Pivot tables along with their charts to make the data more readable and also show quick insights about the Bike Sales Dataset.

## 5. Dashboard

- I created and renamed a new sheet 'Dashboard' to contain all the pivot tables and charts that I made.
- I rearranged all tables, charts to look readable and presentable.
- I also added slicers to my charts to enable interactivity by allowing the selection of different parameters.

## Insights

Male Bike buyers with higher income purchased more bikes compared to females with slightly lower income who did not purchase.
Customers with the least commute (1 mile) own more bikes.

Middle aged people between 31–54 own more bikes than others.

North America has more customers purchase compared to Pacific and Europe region.

Married people purchased 7% more bikes than single people.

## Recommendations

Based on the insights above, I would recommend that bike manufacturers and retailers focus their marketing efforts on male customers with higher income, as they are more likely to purchase bikes. Additionally, middle-aged people between 31–54 should also be targeted as they own more bikes compared to other age groups. Manufacturers and retailers should also consider the commuting distance of potential customers, as those with shorter commutes are more likely to own multiple bikes. Furthermore, the North American market should be a priority as it has more customers purchasing bikes compared to the Pacific and Europe regions. Finally, it is worth noting that married people purchased more bikes than single people, suggesting that family-oriented marketing strategies may be effective.

However, to increase sales, efforts should be made by applying SMART (specific, measurable, achievable, relevant and time-bound) objectives and marketing strategies to convert those who didn’t purchase bikes into customers, especially in the Pacific and Europe regions.

This is the final dashboard.<br>
![](https://github.com/itsmearafik/bike_sales_analysis/blob/main/assets/dashboard.png)
