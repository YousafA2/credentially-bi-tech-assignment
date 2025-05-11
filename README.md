# credentially-bi-tech-assignment

A reference is requested for a specific candidate to verify their reliability with third parties. Once a reference is requested, it goes through the stages of **"submitted"** and then **"reviewed."** It is important to receive and review the reference as soon as possible to speed up the hiring process.  

In the repository, you will find a pre-prepared semantic model along with sources describing references, the job positions for which they were requested, and some other data related to job positions.  

### Task  

1. **Fork the provided repository to your own account.** Please complete the assignment within this forked repository.
2. **Load and analyze the data** that will be used to build this report. What issues do you see with the data, and how can they be addressed?  
3. **Build a simple dashboard** based on the prepared semantic model and some calculations that may be useful to you. Highlight the key metrics that you would emphasize for the client as the most significant in the context of references. Feel free to modify the semantic model/calculations for your purposes.  
4. **When you are finished, please send us the link to your forked repository** with the changes you made, including your dashboard. If you have any questions, please don't hesitate to ask.

### Solution

When analysing the data, numerous issues were found, such as incomplete fields and incorrect data inputs from users (such as job roles not being input correctly). 

In addition, it seems as if multiple employees were assigned to one job role. This could have been due to different people being assigned to review different stages of the review process but there was no clear defintion of this within the semantic model.

To analyse the data, I have highlighted key metrics within the data, such as the average number of days for it to pass from the "Request" to "Reviewed" stage. These key metrics are highlighted at the top of the dashboard, which show key metrics to date, allowing quick comparison of the "to Date" values and any other date periods that need analysis. I have also included trend analysis graphs at the bottom of the dashboard, which shows how key metrics change with time.

For ease of date analysis, I have also included an extra date table which provides more flexibility, where data can easily be split into year, month, quarter etc. Trend analysis is crucial to see which periods during the year may see dips or spikes in the number of days taken. This allows stakeholders within the company to quickly see where improvements can be made. For example, if the days taken to review are longer at certain periods of the year, are there certain factors which are causing this? If so, these can be investigated to potentially reduce review times and improve outcomes for clients.
