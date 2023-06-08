![Header](https://github.com/cmhollman/test_case/blob/main/Data/food_image.jpg)



# USF Test Project 

**Author**: [Chris Hollman](mailto:chollman91@gmail.com)

Thank you for the opportunity to complete this project. Please let me know if you have any questions.

## Questions
-**What is the business objective you are looking to solve for? Specifically, what decisions are you going to inform?**
For the sake of simplicity, a quick look at USF Daily Delivery. This will help identify divisions and segments where the Daily Delivery
service is being used most frequently.

-**Based on your exploration of the data, what insights do you have about our customers?**
Overall USF is outperforming primary competetion in every account category. The vast majority of weekly spending comes from Independent
Restaurant ($6,845,534) and Hospitality ($1,265,565) accounts. USF accounts for 71.63% of reported weekly sales to Independent Restaurants
and 77.22% of reported weekly sales to Hospitality accounts. Independent Restaurants spend $5,087,630 via Daily Delivery service. The
Hospitality segment spends $1,014,461 via Daily Delivery

-**Develop a visualization tool or output that can be used to support the business decisions. What recommendations can you make to the
business?**
A Tableau dashboard summarizing this information is available [Here](https://public.tableau.com/views/USFTestCase/Dashboard1?:language=en
US&publish=yes&:display_count=n&:origin=viz_share_link) Given the high usage of Daily Delivery Service among the highest spending segments
it would be prudent to continue to offer those options to accounts within that category. The Div Number with the highest Daily Delivery
usage among Independent Restauants is 10. Notably, both Hospitality and Independent Restaunts ranked later order cutoff times as most
important to them, so perhaps extending cutoff times would suffice in place of daily delivery service.

-**How would you partner with the broader analytics team (including data scientists) to enhance this analysis?**
It would be useful to look at time stamped historical sales data in these divisions and market segments to identify whether the availability
to order via Daily Delivery has influenced sales totals in any way. If a time series decomposition reveals relativley flat total sales
following the introduction of Daily Delivery then it may not be worth the added cost. 

## Link Summary

See Python code sample in the [Jupyter Notebook](https://github.com/cmhollman/test_case/blob/main/USF_Test_Notebook.ipynb) 

Initial SQL in [BigQuery](https://console.cloud.google.com/bigquery?sq=737860077884:bc2118241c7f47e78c6de0419ba0c6ed)

Visualizations available in [Tableau Workbook](https://public.tableau.com/shared/PRJPPPKWY?:display_count=n&:origin=viz_share_link)

For additional info, contact Chris Hollman at [chollman91@gmail.com](mailto:chollman91@gmail.com)



## Repository Structure

```
├── Data
├── USF_Test_Notebook.ipynb
└── README.md
