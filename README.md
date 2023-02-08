Welcome to my Data Analytics Portfolio where I showcase my various projects ranging from my university's library data occupancy analysis to research in applied mathematics on partial differential equations to model waves such as tsunamis.

# [Project 1: Analyzing library data occupancy data](https://github.com/normatovbekzod/library_data_analysis)
## Aim: 
### Develop 6 stages of the Data Analytics Life Cycle with the aim of analyzing Yale-NUS library occupancy data in order to reveal insights into when the library is the busiest and which sections of the library are under-used.
## Objectives:
 - create a data collection method that can be used by students working for the library
 - clean data using R
 - prepare data for analysis by exporting it in excel format
 - analyze occupancy data using excel and R
 - data visualizations using excel
 - a monthly report with key insights and findings
 - find out which library areas are under-used by analyzing the popularity of each seat (based on occupancy count)
 
## Data collection
Data is collected hourly during library opening hours by students working for the library by manually filling in the qualtrics form. This data collection method is secure as only those with the password to the form could collect data; however, it is also prone to human errors. The dataset is also secure on the qualtrics website and raw data could be downloaded in the CSV format. 

## Data processing
In order to process raw data, R was used. The data processing step involves declaring several functions that help turn raw data into proper and easily understandable parameters. This step involved handling missing data, checking for outliers, which usually indicated a human error during data collection, and checking for duplicates. Processed data was then exported into the excel file.

## Data Analysis and Visualizations
Data analysis involved performing several EDAs and visualizing occupancy counts in various sections of the library throughout the day and how some of the metrics such as average occupancy on weekends and weekdays compare to other months. 
Below are two examples of such visualizations. 
<p align="center">
  <img width="600" height="400" src="image/total_weekday.PNG">
  <img width="600" height="400" src="image/total_weekend.PNG">
</p>

## Reporting and Actions
Main insights and visualizations are included in a monthly report prepared at the start of the following month. This report is saved in Microsoft word format and shared with the library managers. 

# [Project 2: Global COVID-19 vaccination tracker](https://public.tableau.com/app/profile/bekzod.normatov/viz/Global_vax_tracker_2021/GlobalVaccineTracker)
At the end of 2021, I was back home in Uzbekistan and was unpleasantly surprised to find out that my family and friends believed that most of the people in the world are not getting vaccinated and it is only the minority that agrees to get one dose of the vaccine let alone both doses. I could see where they were coming from as the vaccination program in Uzbekistan was very slowly rolling in. As a result, I wanted to create a dashboard where my family and friends could see how the world is giving into the idea of getting vaccinated by visualizing some metrics and plots such as the share of the total population that received one or two doses by country, or region. 

# [Project 3: Sentiment Analysis of movie reviews using nltk data](https://github.com/normatovbekzod/movie_reviews)
The goal of this project is to train a model that would predict whether a given movie review is positive or negative.
- Dataset was taken from nltk movie reviews dataset
- The dataset was split into training and testing sets
- Algorithm used: K-nearest means, TF-IDFs, Singular Value Decomposition(SVD)
- Accuracy rate achieved: 80.6%

# [Project 4: Data Analysis for the Day Care HIV Centre](https://github.com/normatovbekzod/hiv_by_uzb_region)
My volunteer experience at the National Day Care Centre for children and families affected by HIV helped me better understand the problems and stigmas HIV individuals face in Uzbekistan. During my time there I have primarily worked with sensitive data involving HIV statistics. My work involved anonymizing any personal data that could reveal or lead to the identity of the individual as well as helping the centre in its advocacy efforts. I have done that by visualizing some metrics such as the one below on the prevalence of HIV in different parts of Uzbekistan. Unfortunately, due to local legal complexities, most of the output of the data analysis involving HIV statistics cannot be shared openly. However, during my time there I continuously tried to push for better data transparency without violating data anonymity. 

<p align="center">
  <img width="630" height="400" src="image/hiv_by_region_2022.PNG">
</p>

# [Project 5: Unified Transform Lab](https://github.com/normatovbekzod/UTLab_research)
Initial boundary value problems for evolution equations are the problems of finding solutions to evolution partial differential equations satisfying an initial condition and various boundary conditions. Such evolution equations often describe physical systems, with the boundary and initial conditions representing measurements taken at the edges of the spacetime domain. In some circumstances, it is impractical to take measurements at exact points, but easy to measure an average, or weighted average, over an interval. For example, a pressure sensor can only measure the average pressure over its width. Similarly, an opacity sensor measures the average opacity of a substance over the width of its photosensitve cell. In such a circumstance, the exact boundary condition is replaced with a nonlocal condition, representing a weighted average of the pressure, opacity, etc. The resulting problem is known as an initial nonlocal value problem.

While solution of initial boundary value problems for simple evolution equations is well studied, there has been relatively little work on initial nonlocal value problems. The unified transform method was developed around the turn of the millenium, and is uniquely positioned among spectral methods to solve initial boundary value problems of high spatial order. The method was recently adapted (Miller & Smith 2018) to treat an initial nonlocal value problem for the heat equation.

The purpose of this project is to further develop the nonlocal formulation of the unified transform method so that it may be applied to problems for high order evolution equations such as the linearized KdV equation. A possible application is study of wellposedness of the linear part of the celebrated Korteweg-de Vries equation subject to nonlocal conditions.
