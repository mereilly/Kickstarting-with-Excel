# Kickstarting-with-Excel

## Project Overview 
    •The client Louise just barely came short on her fundraising goal. Thus, we are tasked with using a dataset derived from Kickstarter to interpret especially what variables led to successful outcomes for various campaigns of similar natures to that of Louise. Louise's project was in the theater category, as she was fundraising for a play (entitled "Fever"). After reformatting and converting certain elements from the original dataset, we will produce the following deliverables for her to receive in addition to the enclosed report: There will be a file will ".png" files that include charts made to help visualize the campaign outcomes based on their launch dates as well as the outcomes relative to the funding goals. 
### Purpose
    •The purpose is to establish relevant metrics of outcomes and parameters of different fundraising attempts on Kickstarter for Louise to have better guidance on what scenarios would improve her overall chances for success with a similar fundraising attempt. One would have to filter most similar projects based on category-type based variables to create a more relevantly comparable analysis for Louise to reference once the analysis is properly interpreted. We're using subcategories, specifically that of "plays" to further that aim.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

Theater_Outcomes_vs_Launch.png   
    •Using our graph we can see that the lowest curve is outright canceled projects, we can follow the "successful" outcomes curve and see that overall it remains above the failed and canceled attempts. Further, there appears to be a correlation between successful projects and May start dates, but we do not have more information on this specific graph on the duration of those projects or the different variables associated with them. For instance, we know from working with the data that they use different start years,     yet the graph does not distinguish that variable nor others like the number of backers. This graph does not even discriminate between goal amounts, treating success equally even if it came at a larger or smaller amount.  
    •Second, we notice a data gap for canceled projects between September and November months. It does not provide evidence of any hypothesis, but it is an interesting observation potentially worthy of future investigation.

### Analysis of Outcomes Based on Goals


   Outcomes_vs_Goals.png    

•Using this data and that in the Subcategory statistics (Subcategory_Statistics_Outcome_Count_v_Subcategories_of_Theater.png), we can infer that in the theater category, the success rate of fundraising efforts for plays is more than double that of the failures of such efforts for this specific subgroup. 

•Without the subcategory data, it is hard to see an apparent takeaway for Louise. It is however apparent on the Outcomes-based on Goal that the success rates begin to significantly rise at an inflection point of the Goal range 25000 to 29999 but not exceeding about 49999 (percent successful being about 60-100% while in this range), with the failures curve continuing to work in the negative direct relationship.  




### Challenges and Difficulties Encountered
    • Working with a Unix timestamp for the first time reminded me of the need to constantly be looking up terms and relying on my ability to quickly look for answers and solutions. The first challenge without a doubt was simply getting over that hurdle and determining the date conversion formula. It was also imperative to have a keen and flexible understanding of terms used in the downloaded data when compared to instructions given for the analysis (e.g. understanding that the launch date year was the year needed for work in the next spreadsheet following the title of the assignment to gain an understanding of the variable needed to complete the objective).
    • When working with the "Outcomes Based on Goals" Sheet it became very tedious to manually input changes to the formula, albeit for only 13 rows. Manual editing makes it easy for errors to slip through the cracks even with constant review. 
    • Further, while formatting certain equations, I encountered a few syntax issues and error codes. 

## Results
- What are two conclusions you can draw about the Outcomes-based on Launch Date?
    •Potentially we could say that based on the graph derived there is a history of successful projects if your project launch date is in May, but a significantly lower one if you wait to launch in December. While it is a correlative relationship and not a causal one, we can potentially state an outright higher probability based on these statistics.


  
- What can you conclude about the Outcomes-based on Goals?
    •Using this data (of the "Outcomes Based on Goals" and that in the "Subcategory Statistics"), we can infer that in the theater category, the success rate of fundraising efforts for plays is more than double of that of the failures of such efforts for this specific subgroup. This bodes well for Louise. Still, she must consider the limitations of the dataset as a whole in terms of limited representation. She should keep in mind that a formidable goal  (Subcategory_Statistics_Outcome_Count_v_Subcategories_of_Theater.png)  
  
 
- What are some limitations of this dataset?
    • First, organizing the data by month in our pivot tables creates unequal comparisons when considering Kickstarter projects started in the same month but different year. Knowing that the annual contexts held different trends and scenarios calls into question any comparisons made across year variables, even if projects belonged to the same parent category or subcategory. 
    
    • Louise should also consider that this data is being drawn from a limited source (i.e. the Kickstarter platform). There are other variables or trends we may not be accounted for or aware of because of the limited scope of this data even if the sampling size may seem large at first glance. In reality, a few thousand projects across these many years and categories is not a full representation of the general entrepreneurial attempts. 
    

- What are some other possible tables and/or graphs that we could create?
    •We could create a histogram to further visualize and account for any outliers, thereby further clarifying trends. We could also create a pie chart in the category of theater to show how large of its successes are attributed to fundraising for "plays"-- this however may be skewed because of the nature of the larger representation of such projects within the subgroup. 
    •To that end, we may want to create a tale to keep focusing on that subcategory or even in that parent category and establish what minimum fundraising goals had the best chances for success, given Louise narrowly missed her goal. We could also do other tables that take a deeper look at the average percent funded by each individual backer to figure out what is a realistic metric to ask of donors to set and aspire for accounting for further variables not explored above.   


