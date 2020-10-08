# Karachi_Load_Shedding_Blame_Game
Using data from Twitter to determine who is being blamed for load shedding in Karachi, Pakistan.


# Overview
This program seeks to use tweets about load shedding in Karachi, Pakistan to determine what entities are being blamed for the persistent electricity issues the citizens of Karachi have been facing.  This is a project for my Introduction to Data Science class at the University of Maryland Baltimore County, where I have been tasked to use webscraping or an API to gather data, conduct an exploratory data analysis, and develop an informed conclusion about a topic of my choice with the help of data.  I have used the python-twitter API, which is a python wrapper for the Twitter API.  The documentation for the python-twitter API may be found here: 

https://python-twitter.readthedocs.io/en/latest/index.html.

 

# Goals
The fundamental goal of this project is to determine who is being blamed for the load shedding epidemic in Karachi, Pakistan.  As with any programming project, it is also an opportunity to learn how to use different tools.  My learning goals in this project include exploring python libraries like pandas, including visualization tools, learning how to apply an API to collect data, and gaining experience handling a real-world problem with a python program.  


# Motivation & Background
I had the opportunity to attend the Defense Language Institute, where I learned the language and culture of Pakistan for approximately two years.  It was here where I first heard about the problem of load shedding in Pakistan.

The ability to go about our daily lives without needing to worry about access to gas or electricity is, perhaps, the most ubiquitous concept in our society.  What would you do if your access to power was consistently in question?  What if your access to power was cut off for more than 12 hours at a time?  Load shedding has become the way-of-life in Karachi, Pakistan, a city of over 16 million people:

https://worldpopulationreview.com/world-cities/karachi-population

In-fighting between gas and electricity providers has yielded two candidates, Karachi Electric and SSGC, who are being blamed for the energy crisis in Karachi, even as supply shortages expected this winter in Karachi will only worsen the conditions:

https://www.geo.tv/latest/309461-karachi-load-shedding-goes-beyond-12-hours-as-k-electric-ssgc-spar-over-gas-supply

Using social media to determine who is being blamed for load shedding in Karachi, Pakistan has been done on a small scale in the past:

https://www.linkedin.com/pulse/curious-case-k-electric-jamat-e-islami-karachites-aamir-abbasi-cipr-/

This program could offer politicians and public relations teams in Pakistan a systematic way to evaluate where they stand in the Karachi load shedding blame game.


# Table of Contents

Code: There are two data files which you must be aware of:

Karachi_LS_Tweeters

Times_Blamed_Karachi_LS

Both of which can be found on the repository home page:

https://github.com/deshanahan/Karachi_Load_Shedding_Blame_Game

Python NoteBook:
A detailed technical notebook of the code may be found on the repository home page:

https://github.com/deshanahan/Karachi_Load_Shedding_Blame_Game


# Software Requirements
This program uses:
Python programming language
jupyter notebook
Twitter API keys from an imported module contained in a .gitignore file 
Python built-in datetime module
python-twitter module (Twitter API Python wrapper)
pandas module
numpy module

# Data
The dataset is designed to be continuously used and will change based on the number of tweets about Karachi load shedding in the past week.  The captured dataset in the csv files provided on the repository home page are:

Karachi_LS_Tweeters - rows = 8 (blamed entities) columns = 47 (tweeters)

Times_Blamed_Karachi_LS - rows = 8 (blamed entities) columns = 2 (times blamed)

The Twitter API requires authentication through a series of API keys.

The Twitter API allows for:
a maximum of 100 tweets pulled per search
pulling historical tweets of up to one week

All searches in the program utilize the maximum amount of pulls and history that Twitter allows.
