# Home_Sales

![images](https://github.com/Rachel-Rodriguez/Home_Sales/assets/124642442/ecf2af00-b50e-486e-a7d7-5627ae5a1fbb)

In this challenge, you'll leverage your expertise in SparkSQL to extract essential insights from home sales data. Subsequently, you'll utilize Spark to establish temporary views, partition the dataset, perform caching and uncaching operations on a temporary table, and verify the successful uncaching of the table.

Utilize SparkSQL to respond to the following inquiries:

  * #1 What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

  * #2 What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

  * #3 What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

  *  #4 What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

    #1 What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

| Year | AvgPrice |

  +------+----------+

| 2019 | 300263.70 |

| 2020 | 298353.78 |

| 2021 | 301819.44 |

| 2022 | 296363.88 |

+------+------------+
  
    #2 What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

| Date_Built | Avg_Price |

+----------+---------+

|      2010 | 292859.62 |

|      2011 | 291117.47 |

|      2012 | 293683.19 |

|      2013 | 295962.27 |

|      2014 | 290852.27 |

|      2015 | 288770.30 |

|      2016 | 290555.07 |

|      2017 | 292676.79 |

+----------+---------+

    #3 What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.


| Date_Built | Avg_Price |

+----------+---------+

|      2010 | 285010.22 |

|      2011 | 276553.81 |

|      2012 | 307539.97 |

|      2013 | 303676.79 |

|      2014 | 298264.72 |

|      2015 | 297609.97 |

|      2016 | 293965.1 |

|      2017 | 280317.58 |

+----------+---------+

    #4 What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

| Rating | Avg_Price |

+------+---------+

|     0 | 403848.51 |

|     1 | 401044.25 |

|    10 | 401868.43 |

|   100 | 1026669.5 |

|    11 | 399548.12 |
