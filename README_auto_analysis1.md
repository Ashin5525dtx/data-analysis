# Data Analysis Project README

## Project overview

This project conducted exploratory data analysis (EDA) on the 'Auto-DTA' dataset. The dataset contains data on multiple attributes of various vehicles, including fuel efficiency, horsepower, weight, and more, and is often used for statistical analysis and machine learning tasks.

- ### Data set source

  The 'Auto-.DTA' data set was obtained from Consumers Union and licensed by Consumer Reports in April 1979. The information contained in the dataset is primarily used for vehicle performance evaluation.
  The address https://www.stata-press.com/data/r18/p.html

  ### Data set column description

  The data set contains the following (variables) :

  1. **make**: automobile make or model (e.g., Ford, Chevrolet, etc.)
  2. **price**: The price of the car (in US dollars)
  3. **mpg**: Miles per gallon, which indicates the fuel efficiency of the car
  4. **rep78**: 1978 Car Repair History Score (on a scale of 1 to 5)
  5. **headroom**: Headroom inside the car (in inches)
  6. **trunk**: Trunk space (unit: cubic feet)
  7. **weight**: The weight of the car (in pounds)
  8. **length**: Length of the car (in inches)
  9. **turn**: Turning radius of the car (unit: feet)
  10. **displacement**: Engine displacement (unit: cubic inch)
  11. **gear_ratio**: Transmission ratio
  12. **foreign**: Whether it is a Foreign brand (categorical variable: Domestic or Foreign)

  ## Project function

  ### auto_analysis.ipynb

  1. ** Data loading **: Use 'pandas.read_stata()' to load 'auto.dta' data set.
  2. ** Basic Data Exploration **: Displays the first few lines of the data set and the structure of the data (' auto_data.head() 'and' auto_data.info() ').
  3. ** Exploratory Data Analysis (EDA) **: A univariate analysis of the 'price' column is performed to output descriptive statistics.

  ### edaauto.ipynb

  1. ** Data loading **: Load 'auto.dta' data set.
  2. ** Univariate analysis **: Output descriptive statistics of 'price' (price) column, draw histogram, density map and box plot of 'Price'.
  3. ** Correlation Analysis **: Calculate and visualize the correlation matrix between each numerical variable.
  4. ** Relationship between price and other variables **: Use a scatter plot with regression line to show the relationship between 'price' and other variables (such as' mpg ', 'weight', 'length', 'displacement').
  5. ** Pairwise relationship analysis **: Use pairwise relationship diagrams to show the relationship between multiple variables.
  6. ** Category variable analysis **: The relationship between 'foreign' (origin of automobiles) and 'price' is analyzed using boxplot and violin diagram.
  7. ** Pivot Table **: Create pivot table summary 'price' according to the mean and median of 'foreign' (origin).

  ## Use Python packages

  This project mainly uses the following Python packages:

  - **pandas**: Used for data loading and processing, especially loading '.dta 'files.
  - **matplotlib**: Used to create static graphics (such as box plots, scatter plots, etc.).
  - **seaborn**: Used to generate beautiful and informative statistical graphs (such as histograms, heat maps, pair graphs, etc.)

- ）。
