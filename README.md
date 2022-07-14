# PyBer_Analysis

## *The Goal and Methodology*
### In this analysis we had two goals. Our first goal was to summarize the PyBer ride data by ride types and provide a graph showcasing the weekly data trend for the first 4 months of 2019.

---
## *A Data Summary by City Type*
#### In our summary we needed 5 metrics each broken out by type of city:

1. Total Rides
2. Total Drivers
3. Total Fares
4. Average Fare per Ride
5. Average Fare per Driver

The table we used to summarize these data points by city type is shown below. We learned several key points between each city type.

1. Urban Cities
     * Had by far the most rides and drivers had by far the most rides and drivers
     * Had the lowest average fare for both rides and drivers despite the highest total fare dollars
2. Suburban Cities
     * These cities were in the middle for all metrics
4. Rural Cities
     * These cities had the lowest number of rides an drivers
     * They had the highest average fare despite having the lowest total fare dollars

![PyBer Summary Data](https://github.com/05Perseus/PyBer_Analysis/blob/main/Analysis/PyBer_Summary_Dataframe.png)

---
## *How is the School Summary Affected?*
#### When looking at the School Summary we notice big differences in the Thomas High School summary.

1. In our original summary we had the following %'s for passing:
      * Passing Math - **66.9%**
      * Passing Reading - **69.7%**
      * Overall Passing - **65.1%**

![Original School Summary](https://github.com/05Perseus/School_District_Analysis/blob/main/Resources/Original_School_Summary.png)

2. In our updated summary we had the following %'s for passing:
      * Passing Math - **93.2%**
      * Passing Reading - **97.0%**
      * Overall Passing - **90.6%**

![Updated School Summary](https://github.com/05Perseus/School_District_Analysis/blob/main/Resources/Updated_School_Summary.png)

3. Based on the screenshots above it is clear to see that Thomas High School definitely moved up in the ranking as a result of this update. They moved up into the top 5 schools as you can see below:

![Updated School Summary](https://github.com/05Perseus/School_District_Analysis/blob/main/Resources/Updated_Top5_Schools.png)

---
## *What was the affect of the update on other data rollups?*
#### When looking at our other various analysis we had mixed results as detailed below.

1. Passing by Grade
    * This analysis did not change much
    * The only change here was the *NaN* in the 9th Grade column for THS
    * This shows the other data remained intact


*(Original)*<br></br>
![Original Grade Summary](https://github.com/05Perseus/School_District_Analysis/blob/main/Resources/Original_Grade_Summary.png)

<br></br>

*(Updated)*<br></br>
![Updated Grade Summary](https://github.com/05Perseus/School_District_Analysis/blob/main/Resources/Updated_Grade_Summary.png)





2. Scores by Spending
    * This analysis did not change much
    * Scores stayed consistent due to such a small change and the rest of the data staying intact


*(Original)*<br></br>
![Original Spending Summary](https://github.com/05Perseus/School_District_Analysis/blob/main/Resources/Original_Spending_Summary.png)

<br></br>

*(Updated)*<br></br>
![Updated Spending Summary](https://github.com/05Perseus/School_District_Analysis/blob/main/Resources/Updated_Spending_Summary.png)




3. Scores by School Size
    * This analysis did not change much
    * Scores stayed consistent due to such a small change and the rest of the data staying intact


*(Original)*<br></br>
![Original Size Summary](https://github.com/05Perseus/School_District_Analysis/blob/main/Resources/Original_Size_Summary.png)

<br></br>

*(Updated)*<br></br>
![Updated Size Summary](https://github.com/05Perseus/School_District_Analysis/blob/main/Resources/Updated_Size_Summary.png)




4. Scores by School Type
    * This analysis did not change much
    * Scores stayed consistent due to such a small change and the rest of the data staying intact


*(Original)*<br></br>
![Original Type Summary](https://github.com/05Perseus/School_District_Analysis/blob/main/Resources/Original_Type_Summary.png)

<br></br>

*(Updated)*<br></br>
![Updated Type Summary](https://github.com/05Perseus/School_District_Analysis/blob/main/Resources/Updated_Type_Summary.png)



---
## *Conclusion*
In conclusion we replaced the 9th grade scores with *NaN* values for THS. This was only 461 students out of a total 39,170. The changes at the district level were small. However, there were 4 main changes as outlined below:

1. The Average Math score changed by ~0.1 point(s)
2. The Percent Passing Math changed by ~0.2 percentage point(s)
3. The Percent Passing Reading changed by ~0.1 percentage point(s)
4. The Percent Passing Overall changed by ~0.3 percentage point(s)
