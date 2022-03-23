# Homelesness and Programs (2019)

### Abstract

The growing problem of homelessness is a high priority for the state of California. Housing is the greatest factor in reducing homelessness, so how can the government reduce the number of unhoused individuals who are unsheltered? A good goal for California is to implement policies that are effective in rehoming unhoused persons, and reduce the number of unsheltered homeless persons by 7% within a year of implementation.

### Design

After cleaning the data, I created a worksheet that contained the following information, broken down by state: census region, median housing costs per sq ft, the total number of homeless, the total number of emergency shelter (ES) beds, the number of sheltered and unsheltered homeless, information on two population subsets (veterans and transgender/gender non-conforming), and select information regarding mental health and substance abuse services and facilities.

In particular, I focused on programs and services tailored for veterans and LGBT to determine what impact specific, targeted programs have on reducing the number of unsheltered individuals.

### Data

Data for this project was taken from various sites:

- *Point-in-time Counts* for 2019 from the [HUD Exchange](https://www.hudexchange.info/resource/3031/pit-and-hic-data-since-2007/), which contains quantitative and categorical data about the number of homeless individuals (384 rows, 241 columns)
- *Housing Inventory Counts* for 2019 from the [HUD Exchange](https://www.hudexchange.info/resource/3031/pit-and-hic-data-since-2007/), which contains quantitative and categorical data about shelter available to homeless individuals (397 rows, 77 columns)
- a list of census regions and divisions from the [US Census](https://www2.census.gov/programs-surveys/popest/geographies/2016/state-geocodes-v2016.xls)  (52 rows, 5 columns)
- the 2019 National Mental Health Services Survey from [Substance Abuse and Mental Health Services Administration (SAMHSA)](https://www.datafiles.samhsa.gov/dataset/national-mental-health-services-survey-2019-n-mhss-2019-ds0001), which contains quantitative and categorical data about facilities providing mental health services (12,473 rows, 140 columns)
- the 2019 National Survey of Substance Abuse Treatment Services from [SAMHSA](https://www.datafiles.samhsa.gov/dataset/national-survey-substance-abuse-treatment-services-2019-n-ssats-2019-ds0001), which contains quantitative and categorical data about facilities providing substance abuse services (15,962 rows, 246 columns)
- housing price information from [Redfin](https://www.redfin.com/news/data-center/), which contains median prices per sq ft broken down by state (48 rows, 39 columns)

### Tools

- Google Sheets was used for data cleaning and analysis
- Tableau was used to create data visualizations and dashboards

### Communication

Visualizations and dashboards are available on Tableau: [Homelessness and Programs (2019)](https://public.tableau.com/app/profile/sancia7467/viz/HomelessnessandPrograms2019/MapDashboard)