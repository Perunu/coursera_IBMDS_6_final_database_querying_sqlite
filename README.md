# Coursera: IBM Data Science Professional Certificate
## Course 6: Databases and SQL for Data Science with Python

### Purpose:

- The final project for the SQL segment of IBM's Data Science certificate involves using different datasets to answer a set of questions.

**Below is from the assignment itself**
___

## Objective

1.  Understand three Chicago datasets
2.  Load the three datasets into three tables in a SQLIte database
3.  Execute SQL queries to answer assignment questions

## Instructions

### **Understand the datasets**
    To complete the assignment problems in this notebook you will be using three datasets that are available on the city of Chicago's Data Portal:

        Socioeconomic Indicators in Chicago
        Chicago Public Schools
        Chicago Crime Data

### **Store the datasets in database tables**
    To analyze the data using SQL, it first needs to be loaded into SQLite DB. We will create three tables in as under:

        CENSUS_DATA
        CHICAGO_PUBLIC_SCHOOLS
        CHICAGO_CRIME_DATA

### **Use Python/Pandas and SQL to answer questions**

    1. Load the pandas and sqlite3 libraries and establish a connection to the database
    2. Use Pandas to load the data available in the provided links to dataframes. Use these dataframes to load data on to the database as required tables.
    3. Establish a connection between SQL magic module and the database
    4. Proceed to the the following questions

   - Problem 1
      - Find the total number of crimes recorded in the CRIME table.
   - Problem 2
      - List community area names and numbers with per capita income less than 11000.   
   - Problem 3¶
        -   List all case numbers for crimes involving minors?(children are not considered minors for the purposes of crime analysis)
   - Problem 4
        - List all kidnapping crimes involving a child?
   - Problem 5
        - List the kind of crimes that were recorded at schools. (No repetitions)
   - Problem 6
     - List the type of schools along with the average safety score for each type.
   - Problem 7
        - List 5 community areas with highest % of households below poverty line
   - Problem 8
        - Which community area is most crime prone? Display the coumminty area number only.
   - Problem 9
     - Use a sub-query to find the name of the community area with highest hardship index
   - Problem 10
     - Use a sub-query to determine the Community Area Name with most number of crimes.

