# **An Analysis of Kickstarter Campaigns**
## 1) Overview of Analysis
Throughout this project, we were helping Louise using Kickstarter campaign data to find identifiable similarities between successful and failed campaigns based on her interest. As the Kickstarter campaign data came in raw form, we used excel features such as conditional formatting, pivot tables, and charts to organize the data in a fashion that would identify these similarities. 
## 2) Analysis and Challenges
### Analysis
Louise is interested in Theater, so we used outcome results to help determine if there is a better time of year or realistic goal amount that she should consider when launching her Kickstarter campaign to increase her chance of success. Using Pivot Tables, VLookups, Data Charts, and Count formulas, we developed two charts that could visualize the data in a way to identify if her desired variables exist.  
- [Outcomes Based on Launch Date](Resources/Theater_Outcomes_vs_Launch.png)
![Outcomes Based on Launch Date](Resources/Theater_Outcomes_vs_Launch.png)
- [Outcomes vs Goals](Resources/Outcomes_vs_Goals.png)
![Outcomes vs Goals](Resources/Outcomes_vs_Goals.png)
### Challenges
My entire career, I have been using excel, so most of these exercises were easy.  However, because I was lazy in Deliverable 2, I didn't want to type out all the changes in the CountIfs formulas. Therefore, I created *Greater Than and Less Than Columns* so that I could copy the formulas down. While this worked and saved me time when I created the chart, I wasn't able to filter out these columns, so while my chart data was correct, the X-Axis labels were screwed up. To fix this, I copied and pasted it in another section of the workbook as a number. Then I deleted my *Greater Than and Less Than Columns*. After this, I recreated the chart, and I did not have any problems. 
## 3) Results
### What are two conclusions you can draw about the Theater Outcomes by Launch Date?
1. Starting in April, the success rate for campaigns spikes drastically and peaks in May. After which, its success rate starts to decline steadily until September. Therefore, I would recommend creating a Kickstarter campaign between April through June. 
2. While the failed and canceled campaigns numbers are reasonably consistent throughout the year, there is a spike of failed campaigns in October. Also, around October, the declining number of successful campaigns started to close in on the failed campaign numbers and eventually intersect in December. Therefore, I would not recommend launching any campaigns from October to December. 
### What can you conclude about the Outcomes based on Goals?
Having reasonable goals below $5000 is the best way to ensure the success of the campaign because that is when the gap between failed campaigns is most significant. And, success rates are between 60% and 80%. As the goals increase above the $5000 marker, more often than not, there are more failed campaigns than successful campaigns. There is a gap of between $35000-$45000 where there are more successful campaigns than failed campaigns, but after $45000, there is a considerable spike of failed campaigns. So anything campaigns after $45,000 are destined to fail. 
### What are some limitations of this dataset?
These two graphs & data sets cover the easiest and most accessible metrics of successful campaigns such as timing and goal amounts. However, given all the data provided about Kickstarter campaigns.
- [x] We could drill down further
- [x] We look at other data metrics that are not being used. 

A lot of data was given to us by Kickstarter, so we should be using this data to ask questions of why we might see more successful campaigns at certian times of year or why goal rates may matter. 
### What are some other possible tables and/or graphs that we could create?
After determining April through June saw the highest rates of successful campaigns, I want to determine why this may be. My first question would be, should we look at the backer count numbers and *Outcomes Based on Launch* date to see if there is a correlation between year and Kickstarter campaign engagement? Therefore, I could create a line graph to see backer count numbers based on time of year to see if it looks similar to our previous conclusion. 

Maybe average donations and backer counts determine why outcomes based on goals matter. Do goals below $5000 have more donors than goals above $5000? Filtering to successful campaigns, we could use a bar graph at different goal amounts to see how many backers there are. Knowing this information, we may want to adjust our strategy on how we target reaching out to potential backers. Do we try to reach more small donors, or try reaching out to a few big donors. 
