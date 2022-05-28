# surfs_up
## **Overview of Project**

The purpose of this project is to W. examine the information about temperature trends before opening the surf shop. Specifically, we want to show a major investor specific information about temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.
The project utilizes SQLAlchemy to connect to and query a SQLite database and it uses statistics like minimum, maximum, and average to analyze the data.

## Results

 ### June Temperatures 
In June we recorded 1700 measurements, with a mean of 74.9, min of 64.0 and max of 85.0   
  ![IMAGE_DESCRIPTION](/images/june-temps.png)


 ### December Temperatures
  In December we recorded 1517 measurements, with a mean of 71.0, min of 56.0 and max of 83.0
   ![IMAGE_DESCRIPTION](/images/december-temps.png)
 
 ### Additional queries
- To increase the investor's confidence, we added few more queries to count the stations that measured the data and showed how active each station was.
- 
  ![IMAGE_DESCRIPTION](/images/additional-queries.png)
  
 - We also plotted the data for June and December to understand if we had any outliers or skewness in the temperatures curves
 
  ![IMAGE_DESCRIPTION](/images/june-plot.png)
 
  ![IMAGE_DESCRIPTION](/images/december-plot.png)
 
 

## Summary

 - The data shows the average temperatures are in a pleasant range that is not too hot and not too cold year round which is great for the surf shop business.
 - As expected, average temperatures are higher in Jne than in December. But the 5 degrees difference is not so big to expect a big difference in business.
 - Plotting the temperatrures data shows that June temperatures have a more normal bell curve than december with no outliers or skewness.
 - More data and investigation of other factors can be helpful for the shop's success. Other than temperatures, we should examine precipirtation, storms and other weather factors.
