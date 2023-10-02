# Practical-Application-Assignment_5_1

Summary of findings
This project helped me to understand many of the technical concepts of this bootcamp.

I learned how to write code that will use many features of Python and Numpy.
    - Use the pandas set_option to display max columns and rows before you read the files.
    - Use unique() and nunique() to get a list of unique values in the columns.
    - Using the groupby() function is powerful and summarize data to get a better picture
    - 'query()' is fun to use and it helps to use '@' to shorten lines of code
    - Be consistent with variable names
    - Don't recreate a variables with the same data
        - Create it once and try to reuse it
    - There's a difference between a dataframe and a series

I also exercised judgement regarding data and missing values.
    - Never take column names for granted.  
        - Look for typos
            - Fix them by creating a new column with the correct spelling
            - Delete the column with the misspelled name
    - Columns with 'NaN' can affect the results being investigated.
        - Sometimes you don't find out until later on that you have to replace 'NaN'
        - 'get_dummies()' can be useful but 'map()' will allow better control over the new values
        - Don't delete the old columns right away.


 
Link to notebook
http://localhost:8889/notebooks/github/Practical-Application-Assignment_5_1/prompt.ipynb