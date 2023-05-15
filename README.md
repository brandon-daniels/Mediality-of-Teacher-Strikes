# The Mediality of Teacher Strikes: Rhetoric and the U.S. 2018-2019 Movement for Public Education
## Abstract

## How to navigate this repository
This repository contains the code I used in Chapter 4 of my dissertation. I have seperated each step in my research process into seperate Jupyter workbooks. 

First, I obtained my data using the code in [TwitterScraping.ipynb](https://github.com/brandon-daniels/Mediality-of-Teacher-Strikes/blob/main/TwitterScraping.ipynb). This outputs a CSV file with the modest size of 57MB. I have not included this file in the repository in the case that someone deletes their tweets, so that it would not be permentantly recorded on this page. 

Second, I processed the data and created a set of exploratory data visualizations with the code in [RedForEd.ipynb](https://github.com/brandon-daniels/Mediality-of-Teacher-Strikes/blob/main/RedforEd.ipynb). 

Third, I deployed the method of time series topic modelling in the [Time-Series-Topic-Modelling.ipynb](https://github.com/brandon-daniels/Mediality-of-Teacher-Strikes/blob/main/Time-Series-Modelling.ipynb) workbook. ([Thanks to Melanie Walsh!](https://melaniewalsh.github.io/Intro-Cultural-Analytics/05-Text-Analysis/11-Topic-Modeling-Time-Series.html)) to discover coherent word groupings across the dataset of tweets, and I plotted these discovered topics according to the probability that they would appear during certain months of the 2-year period. Topic modelling is an iterative process, and it may require generating multiple models before similar results appear. 

Fourth and finally, [Geoparsing.ipynb](https://github.com/brandon-daniels/Mediality-of-Teacher-Strikes/blob/main/Geoparsing.ipynb) contains the code I used the method of geoparsing ([Thanks to Andrew Haltman!](https://github.com/openeventdata/mordecai)) to discover references to geopgrahic locations and plot them on a map of the United States. 
### Map
A viewable version of this map is available at https://brandon-daniels.github.io/Mediality-of-Teacher-Strikes/
