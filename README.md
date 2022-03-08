# Kickstarting with Excel

**Overview of Project**
Analyzing Kickstarter fundraising campaign data to interpret success and failure rates of campaigns over time.

### Purpose
To identify possible trends in the fundraising data, to better forecast future campaign strategies.

## Analysis and Challenges
The initial challenge with the data set involved cleaning up the data.  Specifically, date format conversion using the Date() function in Excel.  An example of a line of code used:
```
=(((J2/60)/60)/24)+DATE(1970,1,1)
```
Another challenge was categorizing and subcategoriing data, accomplished by using the Convert Text to Columns Wizard, using the / as delimiter.

### Analysis of Outcomes Based on Launch Date
![Analysis of Outcomes Based on Launch Date](https://github.com/maddenc33/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png?raw=true)

### Analysis of Outcomes Based on Goals
![Analysis of Outcomes Based on Goals](https://github.com/maddenc33/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png?raw=true)

## Results

- Two conclusions regarding Outcomes based on Launch Date:
1 The summer months make for the most successful campaign season.
2 The least successful campaign season is during the winter holidays.

- Regarding Outcomes based on Goals, not much can be said except that very low goals have a high success probability, while very high goals have low success probability.

- The main limitation of this dataset is that the only factors being analyzed are goal amount, date, and success rate.  There are undoubtedly other factors that play into the success or failure of a Kickstarter campaign.

- Another possible graph we might create could be a line graph analyzing the dollar amount pledged by month of year, to get a raw number for amount raised, ignoring success or failure of individual campaigns.
