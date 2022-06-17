# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends

#Overview of Project

#For Theater Outcomes by Launch Date the goal was to create a pivot table to visualize the campaign outcomes, successful, failed, and canceled based on launch date. I then created a line graph which allowed me to visually see how successful, failed, and canceled measured up against one another over the year. For Outcomes Based on Goals I used the COUNTIFS() function to see how the financial goal of a theater/play project compares to whether or not it will be successful.

##Analysis and challenges

##To get the years column in the Kickstarter data set I had to utilize the YEAR()function by using the Date Created Conversion column I had created previously. I initially ran into a problem with the Date Created Conversion row. I had to go back to the Kickstarter data set and go to the Date Created Conversion column, and then change the Number section from General to Long Date. After that I had to delete Theater Outcomes by Launch Date and create a new Theater Outcomes by Launch Date. Once I recreated it I was then given Month options for my Row Labels as opposed to just numbers. I could then filter this down further to only show the months. I really struggled with Outcomes Based on Goals until I started copying out the data into new sheets. To get the correct information for Number Successful I had to narrow down the Subcategory column to just plays and the outcomes column to successful. I then created a new sheet and copied the entire Kickstarter data set into the new sheet. I used this same process to create a sheet for Number Failed and Number Canceled. I then used COUNTIFS() and referenced the appropriate sheets I created. I also struggled at first with creating the graph. The graph had too many lines at first so I had to use the Chart filter to remove the unnecessary lines.

###Results

###For Theater Outcomes by Launch Date The first conclusion is that the number of successful plays exceeded the number of failed plays every month. The second conclusion is that there appears to be a season of sorts for plays. The total number of plays was highest in May through August with the largest gap between successful and failed being May. For Outcomes Based on Goals I concluded that projects are more likely to be successful if they have a low budget goal. The higher the budget goal the more likely the project is to fail. For both Theater Outcomes by Launch Date and Outcomes Based on Goals you could create a clustered column chart to show the information as opposed to a line graph. One of the limitations of the data was that it did not tell us much about the category Canceled. All that it really told us was that theater events are rarely canceled. Because they are so rarely canceled, the canceled entries serve as an outlier.

