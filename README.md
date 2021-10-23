# Module-1-Challenge
### Deliverable 1: Outcomes Based on Launch Date Chart 
### Deliverable 2: Outcomes Based on Goals Chart 
### Deliverable, 3: A written analysis of the results (README.md)

# Kickstarting with Excel

## Overview of Project
Given the Kickstart site's campaign data, analysis was completed to find 
expected outcomes for a customer so that they could make informed decisions 
about their own campaign.

### Purpose
The Kickstarting Analysis was completed so that conculsions could be made about
outcomes of campaigns using science and mathematics practices. 

## Analysis and Challenges
The goal was to summarize outcomes using the variables found in the Kickstarter table. 
The primary data columns were: category, subcategory, outcome type, campaign start date,
country and goal amount.

To summarize the data, pivot tables and charts and statistical tables were created
so that specific outcomes could be seen. We also used several other Excel functions 
so that data could be utilized. 

In this module, table data was used to analyze campaign results.

### The following tasks were completed:
``` 
    1. Formatting Data
       - Conditional Formatting
       - Value Shading
       - Averaging Donations
       - Using IFFERROR()
       - Using Text to Columns Feature
       - Converting Unix Timestamps (epoch) to readable format
       - Creating table using VLOOKUP

    2. Creating Pivot Tables and Pivot Charts
       - Using PivotTable Analyze
       - Design Tab Elements
       - Modifying Chart Types
         - Bar and Stacked Bar 
         - Line and Line with Markers
         - Box Plots (Box and Whiskers Plots)
       - Utilizing Chart Elements
 
    3. Analysis of Statistical Data
       - Created Statistical Tables Containing: 
         - Mean (AVERAGE)
         - Median (MEDIAN)
         - Mode (MODE - array Cntl+Shift+Enter)
         - Left/Right Skewed and Skewness 
         - Variance
         - Standard Deviation (STDEV.P and STDEV.S)
         - Range 
         - Quartiles (interquartile, lower and upper) (QUARTILE.EXE)
         - Interquartile Range (IQR) (difference between upper and lower quartiles)
 
     4. Outliers (methods : mean and standard deviation OR median and IQR)
```
### Functions used: 
```
- DATE(), YEAR()
- conversion of epoch date to readable: DATE(1970,1,1) + [epoch date])/60/60/24
- COUNTIFS()
- VLOOKUP()
- AVERAGE(), MEDIAN(), MODE(), STDEV.P(), QUARTILE.EXC()
- ROUND()
- IF(), IFERROR() and nested if statements
- percentage (=x/y*100)
```

### Other Resources used:
##### How to [Convert Epoch Dates to Readable Dates](https://www.epochconverter.com/)			
##### Understanding [Timestamps](https://websiteseochecker.com/blog/what-is-timestamp/)			


### Analysis of Outcomes Based on Launch Date
In this analysis, it was necessary to create a pivot table containing theater outcomes by month. 
We also created a line graph to visualize the pivot table results. 
 
### Analysis of Outcomes Based on Goals
In this analysis, we needed to show play outcomes broke down in goal amount ranges. In the columns, 
we needed to display the counts and percentages of the successful, failed and cancelled plays. We 
were also required to get a Total count of all three outcomes displayed.  

Lastly, I left my percentages with two decimal points in the table. It is bad practice to leave 
percentages in a format that confuses the reader. The last row of the table presents an issue. 
The totals should add up to 100%. They don't. When left rounded with no decimal points, they add 
up to 101%. 

### Challenges and Difficulties Encountered
The nested if statement is cumbersome and very difficult to debug within Excel. Also, within any
other language, you wouldn't do this. You would write a CASE statement. 

## Results

### What are two conclusions you can draw about the Outcomes based on Launch Date?
  1) The month of May seems to be a very good month to launch a play campaign. 
  2) The months having an “R” in them have the greatest likelihood of failing play campaigns. 

### What can you conclude about the Outcomes based on Goals?
  1) The percentage of successful campaigns in the play sub-category have a goal of $5,000 or less. 
  2) The play campaigns with a high percentage of failure were over $25,000. 

#### Other conclusions made during initial analysis: 
     - Failed Campaigns: It seems the higher a goal, the more likely it will fail. 
     - At first inspection it seemed goals over $3000 led to a failed campains; however after 
       futher inspection, their were very large goals contributing to failed goals.
     - Successful campaigns goals fell between $1500 and $5000. 
     - Failed campaigns goals fell between $2000 and $10000.
     - Staying below $5049 would be optimal for success.
     - Average Goal of Successful Campaigns: Louise's goal is double of that average.

### What are some limitations of this dataset?

### Whether Weather Matters

The data doesn’t answer some obvious questions. This leaves me wanting. 
The most obvious to me is the weather. By adding countries in southern 
hemisphere, we might be able to show the effect weather has on a 
successful campaign. 

The reason I believe this is because some four-letter words matter 
(**SNOW, HEAT, RAIN, FALL, WIND**). That is, it has been proven 
weather does matter in many well know studies. It has been used to 
prove humans commit crimes more in the summer, when there is **HEAT**. 
We also have used in studies to know when more babies are born. 
It is in the **FALL** we ‘shack-up’ to make babies. We have also 
used it to study depression. We know when the **SNOW** is falling, 
depression can leak easier into our lives.

### Other Limitations

Wouldn’t it have been nice to know what the MIN and MAX contribution 
of each subcategory was? How about whether there was other advertising 
or insentive utilized to promote the campaigns? 

### What are some other possible tables and/or graphs that we could create?

I would like my graphs to show a story. What kind of story could be told 
if we used deadlines? We have explored the length of a campaign as having 
the effect on outcomes. Looking at the deadlines to see if they might be 
an outcome factor might prove to be of some worth.

Also, we never touched on staff pick and spot light? Do they present an 
effect on outcome? Possibly. We will not know unless we explore them.
