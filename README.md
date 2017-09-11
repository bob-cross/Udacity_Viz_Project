# Udacity_Viz_Project
# Summary
The baseball dataset is a sample of 1,157 Major League Baseball (MLB) players providing their names, height, weight, batting average and home runs hit.
The visual shows a normal distribution of  MLB Batting Averages ranging from .200 to .300 with a mean of .250. Each bar is color coded to show how many players bat right-handed, left-handed or switch hit. The visual highlights batting averages of zero and those below 200; these players are pitchers and often do not bat in MLB. 

# Design
MLB batting averages seemed to be an important aspect of this somewhat limited dataset. Grouping batting averages into uniform ranges seemed to provide a meaningful distribution and such categorical data was then a natural fit for a bar chart. Using the stacked bar chart enabled the visual to incorporate the additional information of the players batting stance. 

# Feedback
Feedback from Josh after looking at the the initial visual version was the clear need to group the data to provide a meaning visual effect. This was accomplished by creating a variable and running a conditional for loop with the floor function and thus grouping the data for graphical presentation.

After making the above adjustments, feedback from Annie involved naming of the axis and the title. The dataset original headers were 'name' and 'avg' which were changed in the CSV to 'Players' and 'Batting Average'. This simple change enhanced the understanding of the graphic.

Now with a fairly robust and concise visual, feedback from Scott was a suggestion to maybe provide a scatterplot overlay of average home runs per batting average grouping. I calculated the average number of HR's per grouping which showed a significant increase as the group's batting average increased. I decided not to incorporate this into my visual. I felt the HR information would detract from the point of my visual which is focused on pitchers (or null values in the dataset), batting average distribution and right-handed vs left-handed batters.

Feedback from my first submission Udacity reviewer was 'we also need that the visualization to center on a specific, clear finding in the data. In other words, this means the visualization needs to be explanatory rather than exploratory'.  Reading the recommendations, I decided to add a summary text block and a line graph of the batting average group peaks.

# Resources
http://dimplejs.org/examples_index.html
https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple.plot#bar
Udacity  forums
numerous Google searches to StackOverflow
