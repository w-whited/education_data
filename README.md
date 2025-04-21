# How Education Relates to Crime and Income In Tennessee



## Table of Contents

*Motivation
*Questions
*Preparing the Data
*Known Issues and Challenges
*Technologies Used
*Data Sources
*Conclusion

## Motiviation
Education has been a big topic in my mind in the past couple years. Before attending the NSS Bootcamp I had just completed my Masters degree. My motivation in
continuing education was to increase my earning potential. As I was searching for ideas to work on for this project I thought this may be something interesting to take a look at. I was curious to see what changes we may see in tennesee counties as we look at areas with higher or lower educational attainment.

##Questions:

1)How have crime and education levels changed over time?

2)Is there a connection between education and household income?

3)How does education level relate to crime rates across counties?

## Preparing the Data
The data that I used for this project, excluding the crime data, was pulled from the American Community Survey API. The API request was for the total population per cpunty as well as a count of adults who had completed the various education levels. Once this was pulled into a data frame I could clean the data, as well as make per capita columns for the education achivements, so that I could compare the counties more acurately. 

The crime data was pulled from the Tennessee Bureau of Investigation using filters such as year, county and type of crime. For both sets I decided to look at five year intervals, beginning at the most recent year available which was 2023. 


## Known Issues and Challenges
Known issues in this project relate to the available data; for example, the population and demographics metrics were collected from the American Community Survey, the ACS has an advantage over the census because this report is created yearly rather than every ten years, but it has some limitations, one being that only communities over a certain size are reported, another being that the data is estimated so this needs to be acknowledged. Another aspect that can be a little difficult is the categorization of crimes, we don't have the most descriptive information of the crimes, but we do have them divided amongst a few categories.

## Technologies Used
Python / Pandas - for cleaning and exploring the data
Power BI - for creating Visualizations
Excel for making quick changes to the data for the visualizations
Google Slides - for building the presentation
Git - for version control

## Data Sources
1) American Community Survey
https://www.census.gov/data/developers/data-sets/acs-1year.html

2) Tennessee Crime Data
https://crimeinsight.tbi.tn.gov/public/Browse/browsetables.aspx

## Conclusion
Through the analysis of the data we do see see increases in the number of adults attaining bachelor's and Graduate Degrees, as well as a significant decline in those who are not completing highschool. Education in tennesse is over all trending in a positive direction. The number of property crimes has decresed over the years in our data set, but the amount of crimes against person and crimes agains property have not signnificantly changed. I have found through analysis a consistent trend showing a rlationship metween educational attainment and median hopuse hold income. I also have identified an inverse relationship between educational attainment and crime rates per county.

