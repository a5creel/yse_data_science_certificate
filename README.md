By Andie Creel 

First updated Dec 21, 2024 
Revised on Feb 26, 2025

# Overview
In this Git repo, I develop 6 lectures for the YSE Data Science Certificate team. Below, I outline the lecture material. 

In these lectures, students begin analyzing data in R and then Python. A PDF of the lecture material accompanies each lecture so students can review it before. An incomplete notebook is provided so for them to syncronously write it during recorded lectures. A complete notebook is provided for reference. All examples are environmentally themed, as well as the problem sets. 

These 6 lectures should included in the Foundations section of the certificate. I have a GitHub lecture may fit better in another section of the certificate. 

# Outline of Six Lectures 
1. **Thinking Like a Computer (45 – 60 min)**
- [Slides](1_think_like_computer.pdf)
   - a. what's programming
   - b. keyword definitions
   - c. problem definition and solution
   - d. why you should code (vs Excel and other software)
   - e. the importance of pseudo-code
   - f. a note on debugging

2. **Base R, Part 1 (51 Minutes)**
- [Complete Jupyter Notebook](final_lecture_material/2_base_R_I/base_R_I_worksheet.ipynb)
- Comments and Basic Data Types:
   - How to write comments in R using the # symbol.
   - The importance of comments for code readability and collaboration.
   - Basic data types in R: numeric (integer and double), character (string), and logical (Boolean).
- Basic Operations and Variables:
   - Performing basic arithmetic operations.
   - Creating and using variables.
   - Changing the value of variables.
- Vectors:
   - Creating and using vectors.
   - Understanding that vectors can only contain one data type.
- Matrices:
   - Creating matrices from vectors.
   - Understanding that matrices can only contain one data type.
- Lists:
   - Introduction to lists and their flexibility in storing different data types.
- Data Frames:
   - Creating data frames and understanding their structure.
   - Referencing columns, rows, and individual cells in a data frame.
   - Adding new columns to a data frame.
   - Assigning meaningful column names to a data frame.

3. **Base R, Part 2**
- [Complete Jupyter Notebook](final_lecture_material/3_base_R_II/base_R_II_notebook.ipynb)
- Functions and Flow Control:
   - How to define and use functions in R.
   - Understanding and implementing loops (for loops).
   - Using if-else statements for conditional operations.
- Global vs Local Variables:
   - The difference between global and local variables.
   - How to use and access these variables within and outside functions.
- Error Handling:
   - Basic error handling techniques using try() and tryCatch() functions.
   - Strategies for debugging and handling errors effectively.
- Simulation:
   - Creating and running simulations using loops.
   - Example of simulating temperature changes over years.
- Apply Functions:
   - Using apply() function to perform operations on data frames.
   - Example of calculating mean temperatures for different parks.
- If-Else Statements:
   - Using if-else statements to correct data based on conditions.
   - Example of adjusting park distances based on gender.

4. **Data Cleaning**
- [Complete Jupyter Notebook](final_lecture_material/4_data_manip_tidyverse/data_manip_tidyverse.ipynb)
- Introduction to Tidyverse:
   - Understanding what packages are and how to install and load them.
   - Overview of the Tidyverse collection of packages for data science.
- Data Manipulation with dplyr:
   - Using `mutate()` to create or modify columns.
   - Using `if_else()` for conditional operations.
   - Using `filter()` to subset data based on conditions.
   - Using `select()` to choose specific columns.
   - Using `group_by()` to group data and perform operations by a category.
   - Using `summarise()` to create summary tables.
- Practical Examples:
   - Examples of manipulating and cleaning data using the functions mentioned above.
   - Real-world scenarios such as adjusting park distances, filtering ecosystems by pollution levels, and summarizing species richness.


5. **Introduction to Datasets**
- [Complete Jupyter Notebook](final_lecture_material/5_intro_data_management/basic_info_datasets.ipynb)
- Reading Data from CSV Files:
   - Using functions like `read_csv()` to load data from CSV files into R.
   - Understanding how to inspect the structure and summary of the dataset using functions like `glimpse()`, `summary()`, and `head()`.

6. **Introduction to Data Visualization**
- [Complete Jupyter Notebook](final_lecture_material/6_data_viz/datasets_vis.ipynb)
- Revisits Data Cleaning and Preparation:
   - Revisits a few techniques for cleaning and preparing the dataset for analysis.
- Creating Plots with ggplot2:
   - Using the `ggplot2` package to create scatter plots and other types of visualizations.
   - Understanding the basic structure of a `ggplot` call, including specifying aesthetics with `aes()` and adding layers like `geom_point()`.
- Facet Wrapping:
   - Learning how to use `facet_wrap()` to create multiple plots within the same graph, separated by a categorical variable (e.g., manufacturer).
   - This allows for easy comparison of the same relationship across different categories.
- Customizing Plots:
   - Adding titles and labels to the plots using the `labs()` function to make the visualizations more informative.
   - Customizing other aspects of the plot to improve readability and presentation.
- Storing and Displaying Graphs:
   - Storing a graph as an object in R and displaying it when needed.
   - This helps in organizing and reusing plots efficiently.

7. **Introduction to Python**
- [Complete Jupyter Notebook](final_lecture_material/7_intro_to_coding_python/python_I.ipynb)
- Understanding the similarities and differences between Python and other programming languages.
- Running basic Python code, such as printing "Hello World".
- Basic Data Types and Operations:
   - Performing basic arithmetic operations.
   - Variable assignment and reassignment.
   - Understanding and using different data types: integers, floating-point numbers, strings, and Booleans.
   - Dynamic typing in Python.
- Data Structures:
   - Creating and manipulating lists, including lists with mixed data types.
   - Using NumPy arrays for numerical data and understanding their similarities to R matrices.
   - Creating and accessing elements in lists and arrays.
- DataFrames with Pandas:
   - Installing and importing the pandas package.
   - Creating DataFrames from NumPy arrays and dictionaries.
   - Renaming columns and accessing columns using both bracket [] notation and dot . notation.
   - Adding new columns to DataFrames.
- Indexing and Selecting Data:
   - Using .iloc[] for integer-location based indexing.
   - Using .loc[] for label-based indexing.
   - Accessing specific rows, columns, and cells using both .iloc[] and .loc[].
- Functions:
   - Defining functions using the def keyword.
   - Writing a function to model a quadratic relationship and returning values.
- Loops:
   - Writing for loops to iterate over ranges and lists.
   - Combining loops with functions to perform repeated calculations.
- Conditional Statements:
   - Using if-else statements to create classifications based on conditions.
   - Iterating over DataFrame rows and using .loc to update DataFrame cells based on conditions.

8. **Datasets and Python**
- [Complete Jupyter Notebook](final_lecture_material/8_python_datasets/python_II.ipynb)
- Data Manipulation with Pandas:
   - Creating and manipulating DataFrames.
   - Selecting specific columns using `loc` or `iloc`.
   - Grouping data and calculating aggregate statistics using `groupby()`.
   - Applying multiple aggregation functions using `agg()`.
   - Adding or modifying columns using `assign()`.
   - Conditionally modifying values using `np.where()`.
   - Filtering rows using boolean indexing.
   - Dropping rows with missing values using `dropna()`.
- Reading in a Dataset and Gathering Basic Information:
   - Reading a CSV file into a DataFrame.
   - Displaying basic information about the DataFrame using methods like `head()`, `tail()`, `shape`, `columns`, `info()`, and `describe()`.
- Basic Data Cleaning:
   - Filtering and cleaning data based on specific research questions.
   - Dropping unnecessary columns.
- Basic Data Visualization:
   - Creating various plots using `matplotlib` and `seaborn`.

9. **Data Cleaning, Part II**
- [Complete Jupyter Notebook](final_lecture_material/9_data_manip_part_II/data_manip_part_II.ipynb)
- `left_join()`
- `pivot_longer()`
- `pivot_wider()`

# Problem Sets

1. [Problem Set One](problem_sets/1_pset_base_R.ipynb)
2. [Problem Set Two](problem_sets/2_pset_R_and_data.ipynb)
3. [Problem Set Three](problem_sets/3_pset_intro_python.ipynb)







