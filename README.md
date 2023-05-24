# The Mediality of Teacher Strikes: Rhetoric and the U.S. 2018-2019 Movement for Public Education
## Abstract
In 2018-2019, US public school teachers and staff went on strikes across multiple states and cities to better their wages, benefits, and working conditions. What began as a seemingly localized protest over health insurance policies in West Virginia, spread rapidly across the country as a “strike wave.” Hundreds of thousands of educators in Oklahoma, Arizona, Colorado, North Carolina, and Kentucky went on strike in the few short months following West Virginia’s action. In the year that followed, some of the largest school districts in the country, like Los Angeles and Chicago, would also launch strikes to halt the divestment of resources in their school districts. These strikes were largely successful in earning raises for teachers and improvements for the state of public education in the United States. This dissertation focuses the rhetoric of the “strike wave” in the sector of public education by examining the relationship between media, publics, and scale. I offer a series of detailed case studies to interrogate the mediality of contemporary labor strikes. Mediality, or the nature of mediation that a particular communication technology engages in, allows me to explore the constitution, and conversely the rapid spread of, the publics that contained the circulation of discourses about the strike. By exploring the scales of public rhetoric, from face-to-face, networked, to global media, I come to understand the mediality of the communication technologies that anchored the existence of these strikes. It is my contention that media provide conditions of possibility for the emergence, expression, and trajectory of the U.S. movement for public education.

## How to navigate this repository
This repository contains the code I used in Chapter 4 of my dissertation. I have seperated each step in my research process into seperate Jupyter workbooks. 

## Prepare Python environment 
In order to set up your environment to run the code, first install all requirements. I use conda. 

`
conda env create -f environment.yml
`

But feel free to also use pip.

`
pip install -r pip-requirements.txt
`
## Navigating workbooks
You need some version of Jupyter to interact with the code in these workbooks. I use the VS Code extension for [Jupyter Notebooks](https://code.visualstudio.com/docs/datascience/jupyter-notebooks).

First, I obtained my data using the code in [TwitterScraping.ipynb](https://github.com/brandon-daniels/Mediality-of-Teacher-Strikes/blob/main/TwitterScraping.ipynb). This outputs a CSV file with the modest size of 57MB. I have not included this file in the repository in the case that someone deletes their tweets, so that it would not be permentantly recorded on this page. 

Second, I processed the data and created a set of exploratory data visualizations with the code in [RedForEd.ipynb](https://github.com/brandon-daniels/Mediality-of-Teacher-Strikes/blob/main/RedforEd.ipynb). 

Third, I deployed the method of time series topic modelling in the [Time-Series-Topic-Modelling.ipynb](https://github.com/brandon-daniels/Mediality-of-Teacher-Strikes/blob/main/Time-Series-Modelling.ipynb) workbook. ([Thanks to Melanie Walsh!](https://melaniewalsh.github.io/Intro-Cultural-Analytics/05-Text-Analysis/11-Topic-Modeling-Time-Series.html)) to discover coherent word groupings across the dataset of tweets, and I plotted these discovered topics according to the probability that they would appear during certain months of the 2-year period. Topic modelling is an iterative process, and it may require generating multiple models before similar results appear. 

Fourth and finally, [Geoparsing.ipynb](https://github.com/brandon-daniels/Mediality-of-Teacher-Strikes/blob/main/Geoparsing.ipynb) contains the code I used the method of geoparsing ([Thanks to Andrew Haltman!](https://github.com/openeventdata/mordecai)) to discover references to geopgrahic locations and plot them on a map of the United States. 

### Map
A viewable version of this map is available at https://brandon-daniels.github.io/Mediality-of-Teacher-Strikes/
