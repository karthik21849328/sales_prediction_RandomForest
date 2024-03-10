# sales_prediction_RandomForest

-------------PART-A-----------------
1. Import necessary libraries.
2. Display a sample of five rows of the data frame.
3. Check the shape of the data (number of rows and columns). Check the general
information about the dataframe using the .info() method.
4. Check the percentage of missing values in each column of the data frame. Drop
the missing values if there are any.
5. Check if there are any duplicate rows.
Proprietary content. © Great Learning. All Rights Reserved. Unauthorized use or distribution prohibited.
6. Check and convert the column StateHoliday to numeric
7. Create a new feature 'recency' from the 'Date' column where,
a) Recency = number of days between the end date and the current date
b) Also drop the columns 'Date' and 'Store'
8. Check the basic statistics of the data-frame using describe() method.

-----------PART -B---------------------
Model Building and Evaluation
1. Store the target column (i.e.Sales) in the y variable and the rest of the columns in
the X variable.
2. Split the dataset into two parts (i.e. 70% train and 30% test) using
random_state=42.
3. Train a Decision tree model
4. Train multiple Decision tree models with different values for max_depth and
max_features
5. Check the importance of features as per the Decision Tree
6. Train a Random Forest model
