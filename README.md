# Data-Preprocessing

This repo includes types of data pre-processing as well as example of finding average of particular column.

There are two types of handling data [ Numerical / Categorical ]

1. Dropping all the columns which includes minimum one null value <br> We will do this with <b>dropna</b> function
2. Adding average values / Replacing Nan with average values <br> We will do this with <b>imputer function</b>

In 2nd type, for numerical data, we can find average value by selecting appropriate strategy <b>(mean / median / most_frequent / constant)</b>. <br>
For categorical data, we we can find average value with the help of most_frequent strategy
