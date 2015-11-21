SNLvDS Shiny Package
========================================================
author: Nicholas Rose
date: November 20, 2015

Package Overview
========================================================

This package was created to allow users ot view the SNLvDS data. This data was obtained to codncut a statistical analysis of which show had better actors/actresses, the Daily Show or Saturday Night Live (SNL) by webscrapping data from Wikepedia, IMDB, and Rotten Toamtoes. The  data from these websites was:

- Cast member tables from [wikepedia] (https://en.wikipedia.org) 
- Movies and TV show list for each actor obtained from [IMDB] (www.imdb.com)
- Audience rankings each TV show or Movie from [Rotten Tomatoes] (www.rottentomatoes.com) 

The code and additional details  can be found [here] (https://github.com/nab2000/SNL-v-DS.git). 

Table Description
=======================================================
After the information was obtained from the web, general statistics were created for every actor/actress, including the mean, median maximum and variance in the audience scores for every movie or show they were in. 

As an exmaple, this is the table of data created for Will Ferrell  


|   |Actor        | BegYear| EndYear|Show | RT_Mean| RT_Med| RT_Max| RT_SD|
|:--|:------------|-------:|-------:|:----|-------:|------:|------:|-----:|
|   |Will Ferrell |    1995|    2002|SNL  |      62|     66|     92|    19|

Shiny Plot Description
=======================================================
The main plot for the project (below) shows the average audience score versus lenght of time on each show

![plot of chunk unnamed-chunk-2](Presentation SNL Shiny-figure/unnamed-chunk-2-1.png) 

SNLvDS Application Advantage 
=======================================================
The [SNLvDS Shiny Application] (https://nab2000.shinyapps.io/SNLShiny), as comapred to the proejct page, allows users to dive more deeply into the data. 

By selecting the actor they are interested in they can see the actor specific table and identify the actor on the main chart 
