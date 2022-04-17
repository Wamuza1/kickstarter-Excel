# kickstarter-Excel
Excel project for analyzing kickstarter

## Overview of Project
Louise who is an up-coming playwright. She wants to start crowdfunding campaigns to help fund her play, Fever. She is estimating a budget of over $10,000. She is hesitant about her first fundraising campaign. She needs our help, as an excel expert to explore the Kickstarter campaigns dataset and help her achieving her goals. 

### Purpose
In this project, we will be using Excel to organizing and sorting crowdfunding data and helping Louise with various analysis, visualizations, and feedback to ensure that she will have a better understanding of campaigns from start to finish.

## Analysis and Challenges
The first step of analysis is to take an initial look at the dataset. There are various columns such as:
Goal column tells us how much money each compaign will need to succeed.
Pledged column shows how much each compaign made.
Outcomes column tells us if compaign met its goal.
Country columns has a list of various countries in which the compaign was started.
We may notice that the data in the columns need to be converted, Dates, in the 
readable format. We need to split categories and sub subcategories. creating new Year column based on the Date Created conversion column. New column for Percentage Funded and Average funded. we need to format the dataset by applying conditional formatting, formulas, and filters to display only the specific data that we want to focus on.

1.The pivot table and pivot chart based on outcomes of the “Parent Category”.

As we can conslude that "Theather" category had the most most successful outcome.Further, we can apply filters to observe the outcomes for each country.

<img width="1195" alt="parent-Category" src="https://user-images.githubusercontent.com/92646311/163236240-d259096b-91b6-4b9b-adba-ac6a96b207bd.png">

 
 2. The pivot table and pivot chart based on outcomes of the “SubCategory”.
 
 we created a new Pivot table and pivot chart, filtered by subcategory to focus our analysis for specific areas that are more relevant for Louise. We can visualize that within the subcategories " Play" was the most successful of all. By filtering for the "US", there were total 3,038 Kickstarter campaigns and the play was the most successful subcategory with 412.For the " Great Britain's " there were 604 Kickstarter campaigns and 238 successful plays.

<img width="1274" alt="subcategory" src="https://user-images.githubusercontent.com/92646311/163236535-395ca7bd-da0a-4143-8005-4fe4f25819f8.png">

 
  3.The pivot table and pivot chart based on overall outcomes of the “Launch Date”.
  
  We can see by looking at our line chart that the months of May and June both had a most successful Kickstarter campaigns.Moreover, in January, June , July, and October all had almost the same number of failed Kickstarter campaigns launched.
  
<img width="1236" alt="Screen Shot 2022-04-16 at 3 15 29 PM" src="https://user-images.githubusercontent.com/92646311/163688478-ca3c5813-92cb-409f-b1d7-49acb0257c8b.png">


 ### Analysis of Outcomes Based on Launch Date

Theater Outcomes vs Launch Date, we have to be more specific with our searches to help Louise plan her campaign. We used pivot chart, filtered the chart by “Theater” we can see that May is the best month to start a successful Kickstarter campaigns as compared to the other months.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/92646311/163688569-50e11876-4712-4251-b670-3f892f231ae9.png)



### Analysis of Outcomes Based on Goals

Three different columns Successful, canceled and failed were created. Then we used advanced formulas,CountIFS() function, Sum(), and logical Operators for analysis. Their coutcomes were calcluted and then converted them into percentages. As we can see, the line graph represents that the less than $1,000  goal range has 76% successfull rate and 24% least failure rate. 

<img width="903" alt="Outcomes_V_Goals" src="https://user-images.githubusercontent.com/92646311/163267921-761d5e4e-7864-441d-a852-9f71926ab3a7.png">


### Challenges and Difficulties Encountered

It was hard to analyze and visualize the Kickstarter campaigns dataset with various graphs. It took time to apply the multiple filters and functions.

## Results

**- What are two conclusions you can draw about the Outcomes based on Launch Date?

1. May looks the best month to start a Kickstarter campaigns.
2. In October,pretty much nothing is canceled, outcomes were either failed or successful.

**- What can you conclude about the Outcomes based on Goals?

Higher goals ranging from $45,000 to over $50,000 have more chances of failing. Whereas goals going below $4,999 had the most successful outcome.

**- What are some limitations of this dataset?

1. How long the campaigns were active to achieve their goals and remained live until the deadline.
2. Secondly, It would be helpful if the cities' names should also be included in the Kickstarter campaigns dataset. It would help to analyze which city performed well to raise the most money. 
3. Any marketing Information If the campaign was marketed.

**- What are some other possible tables and/or graphs that we could create?

We can perform statistical analysis based on the outcomes of the Goal and Pledge columns, successful VS failed. Also, we can uncover the campaign length. We can create box plots, area graph, and scatter graph.
