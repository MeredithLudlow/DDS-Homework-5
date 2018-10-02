# DDS-Homework-5

This is a code book for all the variables created in the Homework 5 rmarkdown file.

Question 1:
df = A data frame consisting of the data read in from the yob2016.txt file. This data contains names, gender, and number of children with popular baby names in 2016.
y2016 = Has the same data as df but with added column names and a mistyped name removed.

Question 2:
df = A data frame consisting of the data read in from the yob2015.txt file. This data contains names, gender, and number of children with popular baby names in 2015.
final = A data set of the merging of y2016 and y2015 by the name column.

Question 3:
Total = A column added to the data frame final of the number of children with a given name from both 2016 and 2015 added together.
ranked = The data frame final that has been ranked in descending order by the total column.
girls = A data frame consisiting of all of the girls's names from the final data frame.
girls_ranked = The girls data frame that has been ranked in descending order by the total column.
Top_10 = A data frame of the the first 10 names from girls_ranked, with only the FirstName and Total columns.
Top10GirlsNames.csv = A CSV file consisting of the data in the Top_10 data frame.
