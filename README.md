

# Labor Statistics using Advanced Tableau

This project is a pilot for labor statistics analystics in the U.S.A. The data source can be found at https://www.bls.gov/. Using web scraping technique in Python, I have downloaded one year of data for the insights. In this repo, I have included the packaged Tableau workbook which includes data needed for all the graphs. 

## Objective/Scope: 
The objectives of the project
1. Study labor force statistics in the USA
2. Analyze employment rates for different sectors/regions
3. Compare economic trends in different industries
4. Evaluate and compare year-over-year growth to understand if 
employment and economy is improving, static, or declining
5. Study the statistics of people claiming Economic Impact Payment 
(stimulus payments)

Requirements: Tableau Desktop 2020.4
## Features:

1. Drilldown from country to county level for detailed analysis
2. Select top N counties per state by industry
3. Analyze employment by education by state
4. Dashboard view with filters and parameters for quick insights
## Key Insights:
1. Across the United States, **Services industries** are employing majority of Population
2. Of all, **California, New York, Texas and Washington** are the top states for employment in the service industries.
3. Top candidates hold **Bachelors degree or some college degree** across the United States

Note: Likewise, the viewer can explore more insights based on his/her interests

## Visualization Highlights:

<img alt="Screen Shot 2021-04-22 at 3 16 02 PM" src="https://user-images.githubusercontent.com/60490190/115772894-a803e880-a37d-11eb-8f42-30a9166d16e5.png">
Sum of Population Estimate 2019 for each State.  Color shows sum of Population Estimate 2019. The context is filtered on State, which keeps 50 of 50 members.

<img alt="Screen Shot 2021-04-22 at 3 18 28 PM" src="https://user-images.githubusercontent.com/60490190/115773416-4728e000-a37e-11eb-9a13-32cde73f71c3.png">
Sum of Population Estimate 2019 for each County broken down by State.  Color shows details about County. The context is filtered on State, which keeps 50 of 50 members. The data is filtered on Action (State). The Action (State) filter keeps 50 members. The Action (State) filter keeps 1 member (Florida).

<img alt="Screen Shot 2021-04-22 at 3 18 42 PM" src="https://user-images.githubusercontent.com/60490190/115773415-4728e000-a37e-11eb-917a-99a96315fcc7.png">
Sum of Annual Average Employment for each Industry.  The marks are labeled by sum of Annual Average Employment. The context is filtered on Industry, which keeps 13 of 14 members. The data is filtered on County, which keeps 1,814 of 1,329 members. The view is filtered on Industry Set, which keeps 13 members.
<img alt="Screen Shot 2021-04-22 at 3 40 05 PM" src="https://user-images.githubusercontent.com/60490190/115775542-041c3c00-a381-11eb-8884-4614cf3e692f.png">
Sum of Annual Average Employment for each Rank County Annual Average Employment broken down by Industry, State and County.  Color shows details about County.  The marks are labeled by sum of Annual Average Employment. The context is filtered on Industry, which keeps 14 of 14 members. The data is filtered on Rank to show, Action (Industry). The Rank to show filter keeps True. The Action (Industry) filter keeps 14 members. The Action (Industry) filter keeps 1 member. 
<img alt="Screen Shot 2021-04-22 at 3 19 03 PM" src="https://user-images.githubusercontent.com/60490190/115773251-15177e00-a37e-11eb-9078-f91c7a60a508.png">
Bachelor's degree or higher, High school diploma only, Less than a high school diploma and Some college or associate's degree for each State.  Color shows details about Bachelor's degree or higher, High school diploma only, Less than a high school diploma and Some college or associate's degree.

### References:
- Web scraped data from https://www.bls.gov/
