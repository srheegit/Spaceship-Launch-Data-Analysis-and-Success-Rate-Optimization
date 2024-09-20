# Spaceship Launch Data Analysios and Success Rate Optimization
In this project, we analyze the Falcon 9 spaceship launch data to analyze the key factors contributing to launch success and apply methods from data science to provide data-driven recommendations to optimize for high launch success rate.

## Overview
This project is meant to deliver key data insights of space rocket launches of SpaceX. SpaceX, the well-known company for spacecraft manufacturing, satellite communications and space launch service, is able to maintain a business edge on space exploration because it reuses parts of its rockets, significantly decreasing their operation cost. According to its website, SpaceX can launch one of its rockets, Falcon 9, with 62 million dollars, while other providers may spend more than 165 million dollars to launch a rocket into space. I'll be exploring the data of SpaceX's Falcon 9 launches, drawing key insights of the data and creating effective machine learning models to predict the success or failure of future launches.

## Further Details and Tools Used
My work involves data collection, data wrangling, data analysis, data visualization, and presentation of my findings. Through REST SpaceX APIs, I accessed data regarding SpaceX's Falcon 9 launches, including launch date, launch success/failure, landing success/failure, the reason of each failure, launch site, and the orbit that a mission traveled in space. Through use of various machine learning models in Python, I was able to predict whether a Falcon 9 launch will succeed or fail with 83% accuracy given its features. I also used Plotly's Dash to create an interactive Dash application, the code of which is included for review.

## Insights
Through data analysis, I have generated several insights of Falcon 9 launches. The key insights are as follows:

 - Among all orbits with at least five launches, Sun-Synchronous Orbit (SSO) is the orbit with the greatest success rate
 - As shown by success rate by year and success rate by flight number, more trials leads to higher success rate
 - Launch site KSC LC 39-A in California has the highest success rate, both overall and for light payload mass
 - Payloads approximately between 300kg and 5330kg – which are relatively light - have the largest success rate
 - FT booster version has the largest success rate

## Recommendations
Based on the above analysis, I have found that the features of a falcon 9 launch that would most likely lead to a successful launch is one with FT booster version, has payload between 300kg and 5330kg, aims for SSO orbit in space, and is launched from KSC LC 39-A Launch site in California.

With this insight, companies can increase their space rocket launch success rate by focusing their resources and research in getting and/or upgrading the booster to FT booster version, developing a relatively light - preferably between 300kg and 5330kg - payloads, aims for SSO orbit in space and, if they had to choose between the four launching sites used by Falcon 9 for a launch site with all other features being equal, use the KSC LC 39-A launch site in California. While correlation does not causation, my data analysis suggests that it may be beneficial to tailor their launches as such.
