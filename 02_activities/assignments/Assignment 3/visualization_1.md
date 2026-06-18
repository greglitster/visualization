## Visualization 1
This visualization was created using the dataset from the Ontario Research Funding Summary webpage found here (https://data.ontario.ca/dataset/ontario-research-funding-summary-current/resource/ebf11cfd-37f7-4775-b2d7-de4f1343787a). The data set provides a summary of research projects funded by the Ministry of Colleges and Universities in the Province of Ontario. The Excel spread sheet is also included in this repository. 


### What software did you use to create your data visualization?

This visualization was created using Python including the matplotlib and pandas packages.

### Who is your intended audience? 

The intended audience of this figure are those interested in applying for research funding or care about municipal economics and showing what part of Ontario most of the research funding has gone to over the last number of years between 2018-2026. 
    
### What information or message are you trying to convey with your visualization? 

I am trying to show which universities have received the most research funding from the Ontario Government and which cities that research funding is going to. 
    
### What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
I was mainly focused on ensuring that the axis labels were representative and easy to interpret with a first glance. Most changes to the generic version of the plot were manipulating the scale of the chart to read more effectively.

Using a stacked bar chart made it easy to show the differences between the cities and which universities were getting the funding at the detriment of specificity of the values. That is, it is difficult to see exactly how much, for example, The Hospital for Sick Children received because they are stacked inside two other institutions. However, the stacked bar chart is helpful for showing the overall scale for each city to show that, for example, Toronto is receiving that much more than Ottawa. 
    
### How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
There is no randomization in the development of this plot so as long as someone else has access to the data set from the link provided, they would be able to create this same plot. 
    
### How did you ensure that your data visualization is accessible?  
I tried to ensure that no two colours representing each of the universities were similar, making it easy to distinguish between the two. 
    
### Who are the individuals and communities who might be impacted by your visualization?
All of the universities that receive funding from the Ontario government, the people who work for the Ontario government, graduate students, researchers and other members of the community that care about the outcomes of academic research.   
    
### How did you choose which features of your chosen dataset to include or exclude from your visualization? 
I selected features based on which would be able to demonstrate the message most effectively. There are many different avenues I could have taken to show the distinction between cities and universities, but this plot was able to convey that message with limited information presented while still making a point. 

### What ‘underwater labour’ contributed to your final data visualization product?
There was some data manipulation (grouping, sorting, adding together) that was required to get to this final visualization. Although the code used for this is not difficult to write, it takes some labour to think through what you want to display. For example, the decision to only include those institutions that have received more than 10 million dollars in funding over that time period was decided based on trial and error becuase lowering that threshold included too many institutions making the visualization too busy. 