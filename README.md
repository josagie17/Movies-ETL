Project Overview

In this module, I learnt how to use the Extract, Transform, Load (ETL) process to create data pipelines. A data pipeline moves data from a source to a destination, and the ETL process creates data pipelines that also transform the data along the way. Analysis is impossible without access to good data, so creating data pipelines is often the first step before any analysis can be performed. Therefore, understanding ETL is an essential skill for data analysis.
Resources

Challenge Overview

In this challenge, I wrote a Python script that performs all three ETL steps on the Wikipedia and Kaggle data. To complete this task, you can use the code you created in your Jupyter Notebook, but don’t just copy and paste! You’ll need to leave out any code that performs exploratory data analysis, and you may need to add code to handle potentially unforeseen errors due to changes in the underlying data.
Challenge Summary

Documented Assumptions:

    The data provided will always be in the correct file format like .json or .csv. If the data provided is not in that format the ETL pipeline will break.
    The spelling of columns names will remain consistent. Columns will not be removed from the datasets.
    The formatting of dollar amounts, dates, times, or other numbers will not change as this could break our regex expressions.
    The sql database tables will not be dropped by anyone else and the data will always be deleted and replaced instead of appended to exisiting data.
    Things like removing adult movies, not including TV shows, and removing rows based on conditions are all built into the function specifically so they can't change their mind later without refactoring the function.
