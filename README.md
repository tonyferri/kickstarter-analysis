# Kickstarter Analysis (2009 - 2017)
An analysis of kickstarter campaigns by country, date, type and goal amount in order to determine the most successful approach.

## Analysis based on date:
Campaigns launched from May through July are the most successful, while the Nov-Dec period contained the least successful.

## Analysis based on goal amount:
The largest positive discrepancies between successful and failed goal amounts is from $25,000 to $30,000 and from $45,000 to $50,000.  Conversely, campaigns of less than $1,000 had the highest degree of failure compared to successful campaigns of the same goal amount.

## Analysis based on category:
Theater campaigns, specifically plays, were the most successful.

## Explanation of Analysis
The graph for theater campaigns based on date shows a large spike in successful kickstarters from May to June while the failed campaigns remains relatively flat in comparison.  Outcomes based on goal amount showed a clear inverse relationship of success to failure in certain groupings.  Finally, theaters and plays for categories and subcategories stood out when compared to others.

[Theater Outcomes Based on Launch Date](https://github.com/tonyferri/kickstarter-analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png)

[Outcomes Based on Goal](https://github.com/tonyferri/kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png)

## Challenges
When I was checking my work on the final tab “Outcomes Based on Goals”, I noticed some slight discrepancies.  I realized that I had used <=1000 in the first row as well as >=1000 in the second row, and I was getting redundant values as a result.  I modified my formula so that the first row was <1000.

## Questions
### What are two conclusions you can draw about the Theater Outcomes by Launch Date?
1)	The most successful campaigns are in May through July (successful campaigns spike, while failed ones remain flat).  One idea is that this could correlate with more people being active this time of year and having the theater / plays more present on their mind?
2)	End of year shows the slimmest difference between successful and failed campaigns; maybe this is due to the holiday season and concerns about spending?

### What can you conclude about the Outcomes based on Goals?
Counter to what I would have expected, campaigns are more successful as the goal amount increases (with the exception of $35,000 to $45,000).  Maybe the lower goals also correlate with a lower confidence of the project occurring, while interest / confidence for the larger projects remain high.

## What are some limitations of this dataset?
Larger scope of time (before 2009; after 2017)

## What are some other possible tables and/or graphs that we could create?
Choosing certain categories and drilling down further into each one (example: top 10)
