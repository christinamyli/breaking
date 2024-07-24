# Breaking Goes Global

### Project Description
As a fan of street dance for a few years now, I knew anecdotally that the US, France, Japan, and South Korea were among the top performers in breaking, but I wanted to look at data to confirm my observations.

This project went through a few iterations before I fleshed out a more interesting narrative that shifted from looking at which countries the top b-boys come from, to one about South Korea's quick ascent in the breaking world. I wanted to work on a project that lended itself well to visuals and also felt timely (given the upcoming Olympics).

### Approach
I wanted to work on a project that focused more on data visualization, thus minimizing the time I would spend on data collection and analysis. Given the visual nature of dance, I thought this topic was well suited for a data visual storytelling project.

### Data Collection
Despite my original goals, data collection ended up taking up a larger chunk of time, since I wanted to find a story worth telling through the data. 

I originally started this project looking at winner results of the Red Bull BC One solo b-boy battles, as a way to look at probable 2024 Olympic breaking winners. The Jupyter notebook attached to this project contains 20 tables with results spanning 2004-2023 that I scraped off the <a href="https://en.wikipedia.org/wiki/Red_Bull_BC_One">Red Bull BC One Wikipedia page</a>. I pulled the data into Excel sheets to clean it, which I then analyzed with Python.

I realized after doing this that there wasn't much of a story angle looking at only 1 competition, so I decided to expand my data collection to other international competitions. I found Wikipedia tables with winning countries for 4 international competitions: <a href="https://en.wikipedia.org/wiki/Battle_of_the_Year">Battle of the Year</a>, <a href="https://en.wikipedia.org/wiki/UK_B-Boy_Championships">UK B-Boy Championships</a>, <a href="https://en.wikipedia.org/wiki/Freestyle_Session">Freestyle Session</a>, and <a href="https://en.wikipedia.org/wiki/Chelles_Battle_Pro">Chelles Dance Pro</a>. I thought this would be an interesting dataset, since these competitions are among the longest-running and also point to the foothold Western countries have had in the breaking world. They are also some of the only competitions with publically available results (the dance world in general is very bad at managing data...).

For simplicity and ease, I made an <a href="https://github.com/christinamyli/breaking/blob/main/Bboy%20Crews%20-%20Country%20and%20Year%20-%20V2.xlsx">Excel sheet</a> listing the year, winning country, and competition name to create one large database. I then analyzed that database in Python to create an area chart with accumulated wins, and bar charts with top countries according to number of wins for each competition. I thought by collecting and analyzing data in this way, I could show that there was something surprising happening in South Korea that I hadn't known before starting this project.

### Data Analysis
Analysis was done with Python - super quick and harmless. 

### Data Visualization
It should be pretty clear that I had the most fun working on the data design. I maybe got carried away with stretching the boundaries of the data viz, but it was a fun exercise in coming up with interesting ideas that incorporated a hip hop theme. Hopefully it's as fun for people to look at as it was for me to conceive/make them!

I first made some preliminary charts in Flourish (area charts, bar charts) and then racked my brain for other ways I could display the charts. All designs displayed on the page were made in Photoshop and Illustrator.

If given more time, I would have experimented with ai2html and After Effects (and also looked at possibly After Effects to HTML??).

### Reflections
This project is not the most interesting in terms of the data that was used. Just getting data off of Wikipedia made me feel like I was taking the easy way out lol.

This also could benefit from more research and reporting. I feel like by the end of the story, I just touched upon the most interesting bit of information, which is that South Korea has had a lot of government backing in dance/arts which could be partially responsible for their ascendance. Just by virtue of living in the United States, I know that government funding for the arts is not really A Thing, so it would have been interesting to compare government funding for dance/arts in both countries. I would also try scraping dance studios that teach breaking in New York City, Paris, and Seoul to get a better sense of what the dance scene is like in those cities. I tried doing a basic search on Google (and Naver in Korean) but would need a better method to make sure I'm collecting as many existing dance studios as possible.
