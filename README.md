# Movie-correlation-project.ipynb

The project involves in data manipulation, analysis, and visualization of movie datasets. 
Here's a breakdown of the steps you performed:

Importing libraries: I imported the necessary libraries such as pandas, numpy, seaborn, and matplotlib for data manipulation, analysis, and visualization.

Reading the data:I read the movie data from a CSV file using the pd.read_csv() function and stored it in a DataFrame called df.

Data cleaning: I checked for missing data in each column of the DataFrame using a for loop and calculated the percentage of missing values for each column. Later, I dropped the rows with missing values using the dropna() function.

Data type conversion: I inspected the data types of each column using the dtypes attribute of the DataFrame. Additionally, I converted the 'gross' and 'budget' columns to integer data types using the astype() method.

Data analysis: I sorted the DataFrame based on the 'gross' column in descending order to analyze the highest-grossing movies. Moreover, 
I then created scatter plots to visualize the relationship between 'budget' and 'gross' using both matplotlib and seaborn libraries. These plots help understand the correlation between the budget allocated for a film and its gross earnings.

Correlation analysis: I calculated the correlation matrix using the corr() method with the Pearson correlation coefficient. The correlation matrix measures the linear relationship between numeric columns in the DataFrame. Later, I visualized the correlation matrix using a heatmap with the help of the seaborn library.

Data numerization: To analyze the correlation between non-numeric columns and other features, I converted the entire DataFrame to numeric form. by using the cat.codes method to convert categorical columns into numeric codes.

Correlation matrix visualization: Finally, I created a correlation matrix using the numerized DataFrame and displayed it as a heatmap using seaborn. This visualization helps identify the correlations between different movie features.

Overall, The project involved data manipulation, analysis, and visualization techniques to explore and understand the movie dataset, particularly focusing on variables such as budget, gross earnings, and their correlations with other features.

