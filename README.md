# Character-Network

Character Network Analysis
Hey there! This repository contains code for extracting and analyzing character networks from works of fiction. A character network is a graph extracted from a narrative, in which vertices represent characters and edges correspond to interactions between them. A number of narrative-related problems can be addressed automatically through the analysis of character networks, such as summarization, classification, or role detection.

For starters, after web scraping to obtain a dataframe of all the characters of the series, I have performed very basic character analysis taking the example of book 7 of the Malazan Series: Reaper's Gale. The visualisation of the character network can be viewed using the .html file.

This project was inspired by Thu Vu’s YouTube video on character network analysis for the witcher series.

The data folder needs to contain a malazan subfolder containing content of each of the books in .txt format.

Getting Started
To get started with this project, clone the repository and install the required dependencies.
```
git clone https://github.com/adithyaGHegde/Character-Network-Analysis.git
cd Character-Network-Analysis
pip install -r requirements.txt
```
