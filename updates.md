## March 21

Searched and found a website featuring datasets containing advanced statistics of European Football. 

## March 23 beginning of class
  
Fixed an error I was getting with the dataset in r where when names had accents in them it would put a question mark in r. Fixed this in excel.

## March 23 end of class

Worked on getting majority of player datasets into data folder and began cleaning it and getting it into r, 

## March 28 beginning of class

Worked on loading the different categories of data into r and worked on tidying issues within all the datasets. Also found another dataset that will contain more subjective football data and began fixing an issue of the names being different in the differing datasets.
 
## March 28 end of class

Mainly worked on learning to create radar charts. Also continued to work on fixing the differing datasets so they have matching names.    

## March 30 beginning of class

Worked on creating the backbone of my shinyapp. Made it so you can select a player and it will show you their individual radar chart. Also continued to work on fixing the differing datasets so they have matching names in excel. 

## March 30 end of class 

Worked on deciding what variables to use for different sub charts and began creating shooting radar chart. Also finished fixing previous issue in datasets with differing names. 

## April 4 beginning of class

Worked on trying to figure out a way to make interactive radar charts. Found ways to make different charts interactive but there is unfortunatly no way to have an interactive chart with variables that have different scales. 

## April 4 end of class

Worked on getting per 90 minute stats for all datasets and had to fix various problems with datasets in excel.

## April 6 beginning of class

Fixed and got all per 90 minute datasets into r and worked on making shooting and shooting per 90 radar charts.

## April 6 end of class

Worked on creating passing radar chart.

## April 11  

Figured out how to make interactive radar charts with the highcharter package and then created plots for passing and defensive stats (both total and per 90 minutes). 

## April 13  

Created charts for shooting and dribbling stats (both total and per 90) and also learned how to add another interactive point to the chart that will later be used to give a written description of each variable.

## April 18 beginning of class

I added interactive points to each chart to each of the charts and made charts (both total and 90) for for goalkeeping stats. Also made tables for each stat and began to load in descriptions of the variables and added them to the charts so when you hover over a variable it displays a description.

## April 18 end of class

Began working with shiny to get a user input for player and then created a tab to show the shooting radar chart and table for that player.

## April 20 beginning of class

Added the passing variable descriptions to the passing plot and then added the plot to the shiny app. Fixed some issues the plots were having in the shiny app and created a theme for the plots.  

## April 20 end of class 

Added a check button to switch between regular and per 90 min graphs and tables and added the shooting and passing 90 min graphs and tables to the shiny app.

## April 25 beginning of class

Added a check button that filters how a players graph will be compared to only players that play their position. Also created a way that will graph players on their ranking of each variable instead of the values themselves.

## April 25 end of class 

Worked on adding a check button to compare the graphs by rank.

## April 27 beginning of class

Finished adding the check button to compare the graphs by rank and figured out how to make tables that are colored by a scaled value.

## April 27 end of class 

Added a button that will allow users to add a second player to compare and began working on a button that will switch the type of graph fro column to area.

## May 2 beginning of class

Added a a button in the side panel to compare two players and also created an image for the players image, club logo and nation flag to show. Also created the datasets for the overall ranking graph.

## May 4

Created a new graph and table for the overall scalings of players. Added all tabs to the app (Overall, Passing, Dribbling, Defending, Possesion) and made them all with interactive graphs and tables the same way that the shooting tab is. Added a table to the side panel feauturing information about selects player(s). Made interactive graph that feature 2 players headshot, club logo and nation flag. Changed shiny background color. 