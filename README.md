# Tableau for Business Users
## Table of Contents

1 Introduction
  1 Why visualize data ? 
  2 Who is this book for ? 
  3 How is this book different ? 
  4 Acknowledgements
  
2 Installation & Setup
2.1 Installation of Tableau
2.2 Data Sources required for the exercises in the book . . . . . . . . . . 9
3 Fundamentals of Data 10
3.1 Data types . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 10
3.2 Data Sources . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 12
3.3 Data Preparation . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 14
3.4 Converting "Business Questions" to the language of Data . . . . . . . 16
4 The Crux of Tableau 18
4.1 The 4 building pillars . . . . . . . . . . . . . . . . . . . . . . . . . . . . 18
4.1.1 Dimensions, Measures & Aggregations . . . . . . . . . . . . . 18
4.1.2 Viz Pane - Columns & Rows Shelf . . . . . . . . . . . . . . . . . 20
4.1.3 Marks Card . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 21
4.1.3.1 Color block . . . . . . . . . . . . . . . . . . . . . . . . 21
4.1.3.2 Size block . . . . . . . . . . . . . . . . . . . . . . . . . 24
4.1.3.3 Label block . . . . . . . . . . . . . . . . . . . . . . . . 26
4.1.3.4 Detail block . . . . . . . . . . . . . . . . . . . . . . . 27
4.1.3.5 Tooltip block . . . . . . . . . . . . . . . . . . . . . . . 28
4.1.4 Filters . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 29
4.2 Putting it all together . . . . . . . . . . . . . . . . . . . . . . . . . . . . 32
4.3 Show Me . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 33
4.4 Sheets & Dashboards . . . . . . . . . . . . . . . . . . . . . . . . . . . . 34
5 Calculations 36
5.1 Grouping values . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 36
5.2 Calculated Fields . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 39
5.3 Row level, Aggregation & Dis-aggregation . . . . . . . . . . . . . . . . 43
5.4 Bringing in more data . . . . . . . . . . . . . . . . . . . . . . . . . . . . 43
5.4.1 From Excel/ CSV . . . . . . . . . . . . . . . . . . . . . . . . . . 44
5.4.2 From MySQL . . . . . . . . . . . . . . . . . . . . . . . . . . . . 48
5.5 Importance of Cardinality - A practical example . . . . . . . . . . . . 49
5.6 Data Modeling . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 52
6 Tables & Table Calculations 55
1
6.1 Show me or from scratch ? . . . . . . . . . . . . . . . . . . . . . . . . . 55
6.2 Table totals . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 58
6.3 Table calculations . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 59
6.3.1 Table & Pane - Down & Across . . . . . . . . . . . . . . . . . . 59
6.3.2 Down then Across & Across then Down . . . . . . . . . . . . . 61
6.3.3 Shortcut to reading Table Calculations in English . . . . . . . 62
6.3.4 Formulation of Table Calculations . . . . . . . . . . . . . . . . 64
6.3.5 Comparisons - YoY, WoW, MoM . . . . . . . . . . . . . . . . . 65
6.4 Sorting . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 67
6.4.1 Nested Sort . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 68
6.4.2 Rank Sort . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 69
6.4.3 Blending Sort . . . . . . . . . . . . . . . . . . . . . . . . . . . . 70
7 Advanced Tips 71
7.1 Dynamic Inputs - Parameters . . . . . . . . . . . . . . . . . . . . . . . 71
7.2 Top 10/20/50 Filters . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 73
7.3 Dual Axis . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 76
7.4 Shapes & Icons . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 77
7.5 Level of Detail (LOD) Calculations . . . . . . . . . . . . . . . . . . . . 78
7.5.1 Fixed LOD . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 79
7.5.2 Include LOD . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 82
7.5.3 Exclude LOD . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 83
7.6 Reference Lines & Forecasts . . . . . . . . . . . . . . . . . . . . . . . . 85
7.6.1 Reference Lines Using Parameters . . . . . . . . . . . . . . . . 85
7.6.2 Reference Lines Using Secondary Data . . . . . . . . . . . . . 87
7.6.3 Forecast & Trend lines . . . . . . . . . . . . . . . . . . . . . . . 87
7.7 Order of Operations . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 88
8 Dashboards 90
8.1 Less is more . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 90
8.2 Dashboards: A view from 10000ft . . . . . . . . . . . . . . . . . . . . . 90
8.3 Fit & Layout . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 93
8.4 Filters & Interactions . . . . . . . . . . . . . . . . . . . . . . . . . . . . 93
8.4.1 Customizing Filters . . . . . . . . . . . . . . . . . . . . . . . . . 94
8.4.2 Discrete vs continuous Filters . . . . . . . . . . . . . . . . . . . 95
8.4.3 Filter Domain . . . . . . . . . . . . . . . . . . . . . . . . . . . . 96
