# How does Salary Increase with Experience?

## Analysis by Trent Pichette

## The Subject

I would like to analyze existing data to determine the relationship between related industry experience and salary.

## The Source(s)

My data is from AskAManager.org's [Salary Survey](https://www.askamanager.org/2021/04/how-much-money-do-you-make-4.html).

### Data Impressions

There seems to be one table; no relationships to manage. The table is quite large, but nothing overwhelming. The dataset, though, is constantly growing. This is where I made the following decision:

I will make this analysis as a static, current-time report, with hopes to make it a dynamic report later down the road.

The latter decision was made to give myself an easier deliverable which can be expanded upon and improved later. Furthermore, there is already a large amount of data, and I won't need to be continuously referring to this data with time; There's an acceptable reason for it not being dynamic and that's because it doesn't really need to be: We don't access it often enough, and the dataset is large enough to reduce volatility in results.

## Approach

### Grand Deliverable

relationship between related industry experience and salary

### Sub-Deliverables

We'll break our deliverable into smaller deliverables as follows:

1. "Establishing the foundation"
     1. Instead of looking at every industry immediately, we'll just focus on one for now (arbitrarily: Nonprofits)
     2. Instead of looking at every source of income immediately, we'll just focus on the annual salary.
     3. Instead of looking at every range of experience immediately, we'll focus on one range: 2-4 years (chosen arbitrarily)
2. "Expanding insights"
   1. We will now begin to analyze two industries worth of data, together and separate, manually (arbitrarily: Nonprofits and Publishing)
   2. We will now begin to analyze two sources worth of income data, together and separate, manually. We'll focus on: annual salary, and additional monetary compensation
   3. We will now focus on two ranges: 2-4 years and 1 year or less (chosen arbitrarily)
3. "Capturing everything available"
   1. Now that we have established analysis of single and multiple industries, we will expand this to include every industry dynamically.
   2. There only seems to be the two variables for income, so no changes here.
   3. Now that we have established analysis of single and multiple years of experience, we will expand this to include every range of experience dynamically.

In the above you can note the exponential growth in the scope our analysis. The third step is commonly the hardest, but certainly the most useful, as it allows our reports to accommodate new and more data while still aligning with the subject of our report.

### Assumptions and Notes

1. We only care about the work experience they have in the field (related industry experience). Overall years of experience (inclusive of non-relevance) is information we can ignore for this analysis.

## Execution

I've broken the execution into general steps I followed:

1. Filtered out irrelevent data using a pivot table on a new sheet
2. Created a chart based on the pivot table to show the relationships between: relevant experience, and income
   1. Since we're using a pivot table, we don't need to create a bunch of separate charts and tables for each scope of data we want to focus on. Instead, we can just modify the filters of the pivot table and the chart will dynamically change.
      1. If you'd like stored reports of certain industries, you can always set the filters as desired on the pivot table, then download the chart as a PDF to save digitally or print! This is better practice than storing reports in an Excel sheet anyways.
3. Using varying filters and analyzing the chart results, I drew a conclusion (which could later be expanded to a rough equation) about the relationship between relevant industry experience and income.
