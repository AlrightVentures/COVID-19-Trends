# COVID-19-Trends

My analysis tries to provide answers to the following questions:

1. Which countries have had the highest number of deaths due to COVID-19?
2. Which countries have had the highest number of positive cases against the number of tests?
3. Which countries have made the best effort in terms of the number of COVID-19 tests conducted related to their population?
4. Which countries were ultimately the most and least affected related to their population?

The dataset was collected between January 20th and June 1st 2020 and contains daily & cumulative number of COVID-19 tests conducted, number of positive, hospitalized, recovered & death cases reported by country. In details here are the columns in the dataset:

- Date: Date
- Continent_Name: Continent names
- Two_Letter_Country_Code: Country codes
- Country_Region: Country names
- Province_State: States/province names; value is All States when state/provincial level data is not available
- positive: Cumulative number of positive cases reported.
- active: Number of actively cases on that day.
- hospitalized: Cumulative number of hospitalized cases reported.
- hospitalizedCurr: Number of actively hospitalized cases on that day.
- recovered: Cumulative number of recovered cases reported.
- death: Cumulative number of deaths reported.
- total_tested: Cumulative number of tests conducted.
- daily_tested: Number of tests conducted on the day; if daily data is unavailable, daily tested is averaged across number of days in between.
- daily_positive: Number of positive cases reported on the day; if daily data is unavailable, daily positive is averaged across number of days in.
