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
 
 ### Requirement 1.3
 A third query retrieves the number of employees by their most recent job title who are about to retire.
 The query reveals that some job titles like senior engineers have thousands of people retiring while other titles like manager only have a handful, so the Silver Tsuname hits differently for different titles.
 
 ![IMAGE_DESCRIPTION](/Data/retiring_titles.png)
 
 ### Requirement 2.
For the second requirement of the project, a mentorship-eligibility table was created to hold the current employees who were born between January 1, 1965 and December 31, 1965. There were 1549 employees identified to be elegible for this program to train for filling the upcoming vacant jobs. The number seems very low compared to the +90k employees set to retire

 ![IMAGE_DESCRIPTION](/Data/mentorship_eligibility.png)
 
 
 ### Requirement 3
 
 Few more queries were developed to answer the following questions
 - How many roles will need to be filled as the "silver tsunami" begins to make an impact?
 - Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

The queries first improved the one developed in requirement 2 by creating a table that groups retiring positions by department and title, then the roles that needed to be filled by department and title were counted. This revealed as can be seen below that the Silver Tsunami does not hit the Engineer job title equally in different departments. Production Department has more to worry about the Quality Management and Research departments

 ![IMAGE_DESCRIPTION](/Data/positions_to_fill.png)
 
 A second query against that table tallied the number employees in lead position which makes them able to help in mentoring the next generation of Employees. This report can be carefully compared to the specific retirement numbers in each department to get a good handle on the severity of the coming problem. But in general the numbers show the ratio of mentors to nthe number of soon-to-be empty positions is very low and indicated the company would get a big hit.
 
  ![IMAGE_DESCRIPTION](/Data/available_staff.png)

## Summary

 - The needs of each department in the Silver Tsunami is different. Some departments will be hit hard whilew others will see very small effect. Mentorship resources should therefore be prioritized and allocated accordingly
 - The company is certainly going to be hurt badly if it does not plan early for this problem. The number of soon to be retired employees and hence the number ofg jobs that will need to be filled is orders of magnitues larger than the number of mentors and qualified replacement staff.
