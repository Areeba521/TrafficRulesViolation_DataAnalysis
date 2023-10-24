

# Traffic Stops and Violations Analysis

This project involves the analysis of traffic stop data to gain insights into the patterns of violations, demographics of drivers, and the impact of certain factors such as race, gender, and stop duration on traffic stops. The analysis is conducted using Python, Pandas, and data visualization libraries.

## Data

The data used in this analysis is obtained from the "file (1).csv" file, which contains information about traffic stops and violations. The dataset includes columns like 'country_name,' 'search_type,' 'driver_gender,' 'driver_race,' 'violation,' 'stop_duration,' and more.

## Analysis

### Data Exploration

- The dataset is loaded into a Pandas DataFrame, and basic exploratory data analysis is performed.
- Information about the dataset's shape, columns, and unique values is gathered.
- Null values in the data are identified using `df.isna().sum()`.

### Traffic Violations

- The analysis focuses on traffic violations, with a specific focus on 'Speeding' violations.
- 'Speeding' violations are separated from the dataset, and statistics about the gender distribution of speeding violations are explored.
- A visual representation of the gender distribution of 'Speeding' violations is provided.

### Stop Duration

- The 'stop_duration' column is mapped to numerical values for better analysis, with '0-15 Min' as 7.5 minutes, '16-30 Min' as 24 minutes, and '30+ Min' as 45 minutes.
- The mean stop duration is calculated.

### Driver Demographics

- The analysis investigates violations by driver race and presents a count of violations for each driver race.
- A cross-tabulation and heatmap visualization are used to explore the relationship between violations and driver race.
- Stacked bar charts are generated to provide a visual representation of the violation counts by driver race.

## Results

The analysis provides insights into traffic violations, highlighting patterns in speeding violations and the demographics of drivers involved in violations. It also offers an understanding of the impact of various factors on traffic stops and violations.

## Next Steps

Further analysis could involve exploring the relationship between driver demographics and violation types, investigating any patterns related to searches conducted, and conducting statistical tests to draw more robust conclusions.

