# DataCollection_Challenge
Module 11

Websites used for assistance:

Writing a file to JSON:
https://www.geeksforgeeks.org/reading-and-writing-json-to-a-file-in-python/
https://stackoverflow.com/questions/71940341/how-to-save-scraped-data-to-json-in-python

Using a dataframe row as header:
https://sparkbyexamples.com/pandas/pandas-convert-row-to-column-header-in-dataframe/?expand_article=1

Clarifying setting xticks:
https://stackoverflow.com/questions/12608788/changing-the-tick-frequency-on-the-x-or-y-axis

Another way to set figure size in pyplot:
https://www.freecodecamp.org/news/matplotlib-figure-size-change-plot-size-in-python/

Sorting data when plotting:
https://www.tutorialspoint.com/how-to-sort-bars-in-a-bar-plot-in-ascending-order-matplotlib

Office Hours Assistance:
When using BeautifulSoup to create my dataframe in mars_weather the values were correct, but everything remained in []. 
Used office hours for assistance, Kranthi went through my workings with me and we realised that in my for loop I was only iterating on the row, rather than also looping through the columns in the rows. 
Was able to insert the below code to resolve my issue.
    values = [column.text for column in row_data]

