# athletic-sales-analysis

## Overview

This analysis focuses on refining and dissecting athletic sales data for a company. The process involved merging dataframes, standardizing and adjusting column names, and filtering large datasets to enhance readability for users. Utilizing the groupby() and pivot_table() functions, several key insights were obtained, including:

- The region with the highest product sales
- The region generating the most revenue
- The retailer with the highest sales volume
- The retailer leading in sales of Women's Athletic Footwear

## Analysis Features

The key main features used to produce this analysis is the use of the groupby() and pivot_table() functions. These two functions made organizing the data into more digestable viewpoints.

## The Process

## Pre-Processing

| Step                                                     | Description                                                                                                                                                                                              |
| -------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Step 1** Import required packages:                     | Import packages and read in 2020 and 2021 csv file .                                                                                                                                                     |
| **Step 2** Combining Dataframes:                         | The first step was combining the data from years 2020 and 2021 together into one dataframe, by rows. This means that the additional data will be listed under the previous data instead of side by side. |
| **Step 3** Convert the date column to datatype datetime: | The 'invoice_date' columns holds date which can be easily accessed by converting the column to a datetime datatype.                                                                                      |

### Most Products Offered 'Total Number of Products' - Region, State, City

                                                            |

| **Step 1** Filter by # of products sold by region, state, city: | In this step, the goal is to separate the data using the groupby() and pivot_table() functions to find the total. The end product should show you the number of product for each region, state, and city. |
| **Step 2** Clean & Sort Data: | Once the data is filtered into region, state, and city we can rename the columns for better visibility and sort the data in descending order to locate the store(s) in a specific region, state, and city that offer the most products on shelf. |

### Most Sales 'Total Sales' - Region, State, City

| Step                                                    | Description                                                                                                                                                                                                                        |
| ------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Step 1** Filter 'total_sales' by region, state, city: | In this step, the goal is to separate the data using the groupby(), applied .sum() to total the sales. Using pivot_table() function, applied the sum function through the aggfunc as a parameter of the pivot_table function 🥵😅. |
| **Step 2** Clean & Sort Data:                           | Once the data is filtered into region, state, and city we can rename the columns for better visibility and sort the data in descending order to locate the top store(s) witht the most sales, listed by region, state, and city.   |

## Key Findings

| **Finding**                                            | **Analysis**                                                                                                                                                                                                                                |
| ------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Number of Products Sold by Region, State, and City** | The most products that an individual store offers is 216 products.                                                                                                                                                                          |
| **Most Sales by Region, State, and City**              | The region, state, city with the most sales totaled $8.28 Million in sales, selling Men's Street Footwear in the Northest region of New York, New York. Women's Apparel followed with sales of $7.8 Million in the exact same region, city. |
| Paragraph                                              | Text                                                                                                                                                                                                                                        |

-

## Learning Experience

## References

[Xpert Learning Asssistant](https://bootcampspot.instructure.com/courses/6028/external_tools/313)
