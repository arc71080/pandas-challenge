# pandas-challenge
Challenge 4 - pandas_challenge

Written Report:
1. District Summary: This data showed the overall district information: the number schools, students, the budget and the overall performance in math and reading.  
        *   As a district, student performance was lower in math than reading.
2. School Summary: This data pulled information for each school in the district to show us the school type, number of students, budget and overall performance in math and reading.  
        *   The majority of charter schools had less students than district schools which made their budget lower and resulted in less money per student.  
        *   District schools math and reading performance mirrored that of the complete district which had students performing lower in math than reading.  Charter schools, however, did perfom lower in math than reading but the difference was not as substantial as the district schools.      
3. Highest and Lowest Perfoming Schools: This data showed which schools perfomred the highest and lowest in the district.
        *   The top 5 performing schools were charter school and the bottom 5 performing schools were district schools. 
4. Math and Reading Scores by Grade: This data showed how each grade level perfomred at each school for reading and math. 
5. Scores by School Spending: this data showed student performance based on how much money is contributed to the student based on the school budget. 
        *   The amount of money per student did not affect student performance as the table shows that less per student actually had a greater overall passing rate.  As noted previously, charter schools had less students than district schools which made their budget lower and resulted in less money per student but charter schools actually have better student performance. 
6. Scores by School Size: this data showed the overall performance based on the amount of students at each school.
7. Scores by School Type: this data showed the overall performance based on the type of school (district or charter).
        *   Again this shows how charter schools performed better on their math and reading compared to district school. 




Sources:
1. https://stackoverflow.com/questions/17839973/constructing-pandas-dataframe-from-values-in-variables-gives-valueerror-if-usi - used these codes to help with errors.  In the data frame, I needed to add the index to the code. 
2. https://github.com/chyu1302/pandas-challenge/blob/master/PyCitySchools.ipynb - used this source to help guide me with the school summary. Major areas I struggled in and helped me with were the school types and math and reading scores.
3. https://stackoverflow.com/questions/72223610/dropping-invalid-columns-futurewarning - used this code to help with errors in the mean. It showed me to add the numeric only.
4. https://pbpython.com/currency-cleanup.html - used this source to help convert the type from other to float so that the amounts would properly bin. 
