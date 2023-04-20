<h1 align="center">
  <a href="https://www.kaggle.com/code/roopamoorthy/google-data-analytics-capstone-project-cyclistic" target="_blank">
    <img src="https://github.com/roopadm/Google-Capstone-Project-R-Tableau-Cyclistic/blob/main/images/1650821003822-removebg-preview.png" alt="Cyclistic" width="60" height="50" style="vertical-align: middle;"/>
  </a>
  <strong>Data-Driven Marketing Strategies for Rider Conversion : Rider Usage Analysis with R and Tableau</strong>
  <a href="https://public.tableau.com/app/profile/roopa.d.moorthy/viz/GoogleDataAnalyticsCapstoneProjectRiderUsageAnalysis/PopularStationsAnalysis?publish=yes" target="_blank">
    <img src="https://github.com/roopadm/Google-Capstone-Project-R-Tableau-Cyclistic/blob/main/images/tableau_logo-removebg-preview.png" alt="Tableau" width="50" height="50" style="vertical-align: middle;"/>
  </a>
</h1>

Join me on my data-driven journey through the data of Cyclistic, a bike-share company in Chicago, we will explore how annual members and casual riders use their bikes differently. Utilize R for data cleaning and manipulation, and Tableau for data visualization, to seek answers to three key questions:

- How do annual members and casual riders use Cyclistic bikes differently?
- Why would casual riders buy Cyclistic annual memberships?
- And how can Cyclistic use digital media to influence casual riders to become members?

## Goal

To uncover insights into rider usage patterns, identify the factors that drive casual riders to become members, and develop marketing strategies that will make it happen.

<b>For fully narative version of this project : <a href="https://www.kaggle.com/code/roopamoorthy/google-data-analytics-capstone-project-cyclistic">check out my Kaggle notebook.</a></b>

<p align="center"> <a href="https://www.kaggle.com/code/roopamoorthy/google-data-analytics-capstone-project-cyclistic" target="_blank"> <img src="https://github.com/roopadm/Google-Capstone-Project-R-Tableau-Cyclistic/blob/main/images/Rider%20Usage%20Analysis%20Google%20Data%20Analytics%20Capstone%20Project.png" alt="Projectimage" width="80%" height="10%"/> </a> </p>

## Dataset 

Public data of Cyclistic’s historical trip data is available on <a href="http://divvy-tripdata.s3.amazonaws.com/index.html">Motivate International Inc. </a> under the  <a href="https://ride.divvybikes.com/data-license-agreement"> license. </a>

I have used 12 months of data , April 2020 to March 2021. To get a brief look used MS Excel and noticed each month's data is recorded in separate CSV files with fields such as ride id, rideable type, start and end time, start and end station, latitude, and longitude of the start and end stations.

####

**Prerequisite:** <code>[R](https://www.w3schools.com/r/)</code> :hourglass: , <code>[Data analysis with R](https://www.coursera.org/learn/data-analysis-r)</code> 📑, <code>[Tableau](https://www.tutorialspoint.com/tableau/index.htm)</code> :hourglass: & <code>[Statistics and probability](https://www.khanacademy.org/math/statistics-probability)</code> 🗂️


## Technologies used ⚙️

* <a href="https://www.kaggle.com/code/roopamoorthy/google-data-analytics-capstone-project-cyclistic">R</a> <a href="https://www.kaggle.com/code/roopamoorthy/google-data-analytics-capstone-project-cyclistic" target="_blank"> <img src="https://github.com/roopadm/Google-Capstone-Project-R-Tableau-Cyclistic/blob/main/images/r.png" alt="R" width="30" height="30"/> </a>

* <a href="https://public.tableau.com/app/profile/roopa.d.moorthy/viz/GoogleDataAnalyticsCapstoneProjectRiderUsageAnalysis/PopularStationsAnalysis?publish=yes">Tableau</a><a href="https://public.tableau.com/app/profile/roopa.d.moorthy/viz/GoogleDataAnalyticsCapstoneProjectRiderUsageAnalysis/PopularStationsAnalysis?publish=yes" target="_blank" rel="noreferrer"> <img src="https://github.com/roopadm/Google-Capstone-Project-R-Tableau-Cyclistic/blob/main/images/tableau_logo-removebg-preview.png" alt="JupyterNotebook" width="25" height="25"/> </a>

##### R Libraries : 
* <a href="https://www.tidyverse.org/">Tidyverse</a><a href="https://www.tidyverse.org/" target="_blank" rel="noreferrer"> <img src="https://github.com/roopadm/Google-Capstone-Project-R-Tableau-Cyclistic/blob/main/images/Tidyverse.png" alt="tidyverse" width="30" height="30"/> </a> |  <a href="https://cran.r-project.org/web/packages/skimr/vignettes/skimr.html">Skimr</a><a href="https://cran.r-project.org/web/packages/skimr/vignettes/skimr.html" target="_blank" rel="noreferrer"> <img src="https://github.com/roopadm/Google-Capstone-Project-R-Tableau-Cyclistic/blob/main/images/skimr.png" alt="skimr" width="30" height="30"/> </a> |  <a href="https://dplyr.tidyverse.org/">dplyr</a><a href="https://dplyr.tidyverse.org/" target="_blank" rel="noreferrer"> <img src="https://github.com/roopadm/Google-Capstone-Project-R-Tableau-Cyclistic/blob/main/images/dplyr.jpg" alt="dpylr" width="30" height="30"/> </a> |  <a href="https://www.rdocumentation.org/packages/janitor/versions/2.2.0">Janitor</a><a href="https://www.rdocumentation.org/packages/janitor/versions/2.2.0" target="_blank" rel="noreferrer"> <img src="https://github.com/roopadm/Google-Capstone-Project-R-Tableau-Cyclistic/blob/main/images/janitor.jpg" alt="Janitor" width="30" height="30"/> </a> |  <a href="https://lubridate.tidyverse.org/">lubridate</a><a href="https://lubridate.tidyverse.org/" target="_blank" rel="noreferrer"> <img src="https://github.com/roopadm/Google-Capstone-Project-R-Tableau-Cyclistic/blob/main/images/lubridate.png" alt="Lubridate" width="30" height="30"/> </a>

## To answer the key business questions : 🔍

Six steps of the data analysis process


1. Ask

2. prepare

3. process

4. analyze

5. share

6. act 

Also,certain roadmap is followed :

* Code, if required.
* Guiding questions and their answers
* Key tasks and deliverables as a checklist.

## ASK : First step of data analysis process

<b> `Business task` : Understand Annual and casual rider usage patterns to recommend marketing strategies to convert casual riders into annual members and how digital platforms could influence them. </b>
 
## Prepare : Second step in data analysis process:

`Data collection, identify how data is organized and determine data creadibility`.

## Process : Third step in data analysis process

`  Choose a tool for data cleaning, check errors in data, and document the cleaning process.`

 I have used R language to import the dataset and check how the data is organized and ensure all the columns has the right data type.

`Load Libraries`

 `import CSV files for each month`
 
 `know the structure data frames`
 
 <b>* DATA CLEANING </b>
 
 Decided to removed missing/blank values to make the merging all CSV files into one dataframe easier.
 
 ` removed duplicated ride IDs`
 
 ` convert date/timestamp to date/time `
 
 ` create separte start and end date of trip `
 
 ` create columns for month,day and year for all rides `
 
 
<b>* DATA MANIPULATION  </b>
 
 ` new column - duration and check for trip duartion in mins less than 0 `
 
 ` filter to include rows with duration greater than 0 `
 
 ` Arranging data in ascending order `
 
 ` Save the clean data as CSV file `
 
 ## Analyze
 
 1. Data Distribution : rider type
 
 ` What is the percentage of Annual members and casual riders? `
 
 2. Monthly analysis : Rider type
 
 3. Weekly Analysis

` Data Distribution by days of the week`

## Share 

For the share phase, the CSV file "Trips.csv" after cleaning is visualized in <a href ="https://public.tableau.com/app/profile/roopa.d.moorthy/viz/GoogleDataAnalyticsCapstoneProjectRiderUsageAnalysis/PopularStationsAnalysis?publish=yes">Tableau for presentation </a>.

1. <a href ="https://public.tableau.com/app/profile/roopa.d.moorthy/viz/GoogleDataAnalyticsCapstoneProjectRiderUsageAnalysis/PopularStationsAnalysis?publish=yes">Trip Distribution </a>

<p align="center"> <a href="https://public.tableau.com/app/profile/roopa.d.moorthy/viz/GoogleDataAnalyticsCapstoneProjectRiderUsageAnalysis/PopularStationsAnalysis?publish=yes" target="_blank"> <img src="https://github.com/roopadm/Google-Capstone-Project-R-Tableau-Cyclistic/blob/main/images/Trip%20Distribution.png" alt="Countries" width="80%" height="50%"/> </a> </p>

2. <a href ="https://public.tableau.com/app/profile/roopa.d.moorthy/viz/GoogleDataAnalyticsCapstoneProjectRiderUsageAnalysis/PopularStationsAnalysis?publish=yes"> Trip Analysis by Months </a>

<p align="center"> <a href="https://public.tableau.com/app/profile/roopa.d.moorthy/viz/GoogleDataAnalyticsCapstoneProjectRiderUsageAnalysis/PopularStationsAnalysis?publish=yes" target="_blank"> <img src="https://github.com/roopadm/Google-Capstone-Project-R-Tableau-Cyclistic/blob/main/images/Trip%20Analysis%20by%20Months.png" alt="Countries" width="80%" height="50%"/> </a> </p>

3. <a href ="https://public.tableau.com/app/profile/roopa.d.moorthy/viz/GoogleDataAnalyticsCapstoneProjectRiderUsageAnalysis/PopularStationsAnalysis?publish=yes"> Trip anlayis by Hour </a>

<p align="center"> <a href="https://public.tableau.com/app/profile/roopa.d.moorthy/viz/GoogleDataAnalyticsCapstoneProjectRiderUsageAnalysis/PopularStationsAnalysis?publish=yes" target="_blank"> <img src="https://github.com/roopadm/Google-Capstone-Project-R-Tableau-Cyclistic/blob/main/images/Trip%20Analysis%20By%20Hour.png" alt="Countries" width="80%" height="50%"/> </a> </p>


4. <a href="https://public.tableau.com/app/profile/roopa.d.moorthy/viz/GoogleDataAnalyticsCapstoneProjectRiderUsageAnalysis/PopularStationsAnalysis?publish=yes"> Popular start and end Station Analysis </a>


<p align="center"> <a href="https://public.tableau.com/app/profile/roopa.d.moorthy/viz/GoogleDataAnalyticsCapstoneProjectRiderUsageAnalysis/PopularStationsAnalysis?publish=yes" target="_blank"> <img src="https://github.com/roopadm/Google-Capstone-Project-R-Tableau-Cyclistic/blob/main/images/Popular%20Stations%20Analysis.png" alt="Countries" width="80%" height="50%"/> </a> </p>

 
