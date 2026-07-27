# GDP-Changes-During-CoVID-Pandemic
Excel Analysis and Dashboard Showing Effect of CoVID19 Pandemic on Economies (GDP) Around the World

## Table of Contents

* [Header](#header)  
* [Dataset](#dataset)  
* [Technologies Used](#technologies-used)  
* [Analysis and Visualisations](#analysis-and-visualisations)
* [Conclusion](#conclusion)

## Header

- **Motivation:** Having just lived through a huge global pandemic, we've seen the world go through the biggest recession, but we've also seen different countries cope in different ways.  
- **Objective:** I aimed to determine the economic impact on the world as a whole, as well as find patterns in which countries were most and least affected. I also became curious about whether this comparison could be biased by different reporting measures of Nominal GDP versus PPP GDP
- **Learning Outcomes:** Skills in data cleaning with PowerQuery, lessons in version control and regular saving. And I learned not to assume Nominal and PPP GDP are always the same - they both have their uses but the outcomes will not always be equivalent.

## Dataset 
Original source unknown - data obtained as part of a Data Analysis course with ITonlinelearning
Dataset Size: 5 columns, 195 rows
Columns:
- Country
- Nominal GDP per Capita
- PPP GDP per Capita
- GDP growth percentage
- Rise/Fall GDP Category (based on size of rise or fall)
Preprocessing steps
- In Excel PowerQuery, imported the CSV file and promoted headers
- Changed data types: GDP columns to 123, country column to ABC
- Dropped duplicate country rows
- Capitalised Rise/Fall categorical column for consistency and accurate filtering
- Dropped nulls from Nominal GDP per Capita (data was missing for Syria) by simply deselecting these in filter
- Renamed Columns for readability
- Changed GDP columns to currency type
- Converted growth percentage column to percentage type (divide by 100 then convert)


## Technologies Used
<ul>
  <li><strong>Languages & Libraries:</strong> Excel</li>
  <li><strong>Tools:</strong> PowerQuery </li>
  <li><strong>Data Visualization:</strong> Excel</li>
</ul>

<img src="https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Excel"

## Analysis and Visualisations
<img width="1819" height="886" alt="image" src="https://github.com/user-attachments/assets/91ba36b2-c847-482a-be0b-3c5417ed8ffe" />
<img width="1816" height="513" alt="image" src="https://github.com/user-attachments/assets/fc8c01c8-2560-4bc4-88fe-a3b94c111fbf" />

The majority impact of the CoVID-19 pandemic was a fall in the economy globally and in the majority of countries, including both stronger and weaker economies, with only 10% of countries showing ideal economic growth (+0-3% GDP). Countries with already weaker economies had the potential to be most affected, with several experiencing ~20% fall in GDP. A few poorer countries experienced a slight to medium rise in GDP of up to 6%. Only Guyana was an extreme outlier with a 43% rise.

This pattern likely means global recession, and is a problem for employees, businesses and their investors: less income, less spending. The decrease in Purchasing Power Parity (PPP) GDP occuring in the majority of countries indicates a global decline in standard of living due to reduced ability to pay for goods and services in each country. A fall in economy may be expected due to the effects of lockdowns, and further exploration into prior and later years' data to determine whether this is a temporary or lasting effect.

## Conclusion:
The effect on the economy during CoVID19 was largely negative, more so for those with already weaker economies. With PPP dropping globally, consumer demand will reduce for non-essential items. This suggests businesses should aim for lower operational costs shift offerings toward essential goods and services during times of crisis. International relief aid could be targetted toward the most affected countries, using PPP GDP for this decision making as it reflects purchasing power within that country and is therefore better for poverty relief decisions.

Extreme outliers like Guyana warrant local research to understand their high performance during the crisis, and further more recent data could be added to this to allow recovery trend mapping across countries.

## License
This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/) – feel free to use and modify it.  


