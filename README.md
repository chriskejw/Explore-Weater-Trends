# Udacity Data Analyst Nanodegree | Project 1 |
- Explore Weather Trends

# Objectives

- To analyse local and global temperature data and compare local temperature trends to overall global temeprature trends.
- Create a visualisation and write up describing the similarities and differences.

# Built With

- SQL, Python

# Data Source

- udacity.com

# Step 1: Extract data using SQL
- **To get the city data of Singapore, I used country = ‘Singapore’ because I know that Singapore is a city state, so the city of Singapore is Singapore.**

  SELECT * 
  FROM city_data 
  WHERE country = 'Singapore'
  
- **To get the global data**

  SELECT * 
  FROM global_data 

# Step 2: Download CSV of both data

# Step 3: Use Python and Jupyter notebook 
- Key Considerations & Steps Taken: 
  1. Impute the mean for any missing temperature values in the Singapore data;
  2. Calculate the 7 years moving averages for both datasets;
  3. Remove the preceding years in the global data to align it with the Singapore data; 
  4. Overlay both graphs to obtain a better visualisation for comparison and analysis.

# Author

- Chris Ke

# Credits

- udacity.com
- w3schools.com
- stackoverflow.com
- and google.com (of course!)

# Contact

- This is my first data analyst project. Please feel free to drop me a mail at chriskejw@gmail.com if you have any ideas or suggestions to make this better. Thanks!
