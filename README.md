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

| Step                                                            | Description                                                                                                                                                                                              |
| --------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Step 1** Import required packages:                            | Import packages and read in 2020 and 2021 csv file .                                                                                                                                                     |
| **Step 2** Combining Dataframes:                                | The first step was combining the data from years 2020 and 2021 together into one dataframe, by rows. This means that the additional data will be listed under the previous data instead of side by side. |
| **Step 3** Convert the date column to datatype datetime:        | The 'invoice_date' columns holds date which can be easily accessed by converting the column to a datetime datatype.                                                                                      |
| **Step 4** Filter by # of products sold by region, state, city: | In this program, we were tasked with using the groupby() and pivot_table() functions to find the total.                                                                                                  |

1.  Filter by the number of products in each region, state, and city (groupby, pivot_table)
2.  Call the count() function to find the total number of products for each region, state, city.
3.                                                          |
    | **Step 5** Filter by # of products sold by region, state, city: | The 'invoice_date' columns holds date which can be easily accessed by converting the column to a datetime datatype. |

## Key Findings

By combining 2020 sales and 2021 sale data these are some of the findings discovered through the use of the learned data analysis tools covered in Week 5 of bootcamp.

-

## Learning Experience

## References

[Xpert Learning Asssistant](https://bootcampspot.instructure.com/courses/6028/external_tools/313)
