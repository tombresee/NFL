---
title: Milestone
---



## <font color='maroon'>Milestone - University of Michigan</font>

<br>
<br>

### <font color='maroon'>Project Name: NFL-Eval</font>

The **purpose** of this project is to create an extended EDA template for National Football League (NFL) football stats by merging multiple key raw data sources.  Data sources will have differing access mechaisms such as HTTPS, API, and .csv forms.  The endgoal is to then create tailored representations of NFL play information to derive insights and deeper understanding of the nuances of the NFL plays.  These types of analyses are becoming more popular as the NFL releases [Next Gen Stats](https://nextgenstats.nfl.com/) to the public, and begins to embrace analytics and machine learning. Football is America's most popular sports and is a billion dollar enterprise.  


<br>
<br>


### <font color='maroon'>Core Raw Data Sources:</font>
 - [Kaggle NFL Repo](https://www.kaggle.com/c/nfl-big-data-bowl-2021/data)
   - **Description:** Online resource of 2018/2019 football season raw data, including GPS-like positional information for every single player for every single play (offense and defense). 
   - 20 separate .csv files (including one with 18M samples), and 363 feature columns
   - Total Set Size:  2.17 GB
   - Accessible via kaggle web API

 - [NFL Kaggle 2020 Repo](https://www.kaggle.com/c/nfl-big-data-bowl-2020/data)
   - Total Set Size:  276.47 MB
   - Accessible via kaggle web API 

 - [NFL Next Gen Stats](https://nextgenstats.nfl.com/)
   - Multiple insightful data sub-sources accessible via web scraping of raw HTML

 - [NFL Play by Play Vault](https://www.dolthub.com/repositories/Liquidata/nfl-play-by-play)
   - This data sourced from original nflfastR package scrape of [this](https://github.com/guga31bb/nflfastR-data)
   - Original poll python [scripts](https://github.com/dolthub/dolthub-etl-jobs/tree/master/adhoc/nfl-play-by-play)
   - Assumption is via Dolpy, a python API [wrapper](https://www.dolthub.com/docs/tutorials/installation/#doltpy)

 - NFLsavant.com
   - http://nflsavant.com/pbp_data.php?year=2018
   - 45,000+ play breakout samples 

 - Potentially public access to [Shield](https://api.nfl.com/docs/getting-started/index.html)
   - Shield represents the client-facing API that will serve the needs of internal projects, external contributors, and third-party partners. It is the primary way to read and write content to the NFL. It will allow users to find content, submit content for use in client applications and websites.
  - [API Endpoints](https://api.nfl.com/docs/global/endpoints/index.html) 
    - This is a full list of the available Shield API root nodes.


<br>
<br>


### <font color='maroon'>Expected Data Manipulation:</font>
 - Initial Processing:
   - Expected 
- Merging/Combining:
   - Joining of all datasets will be contingent on a few elements:
     - In some cases, unique gameID key will be used to merge dataframes (which can also be broken out by NFL week)
     - In some cases, unique playID key will be used to merge dataframes
     - In some cases, unique playerID key will be used to merge dataframes
   - The outputs of the combinations and merges of the raw datasets will be dataframes that contain valuable meshed data forms that will allow correlation of features and examination of factors leading to victories (or football game losses).  
- New information resulted from combining them:
   - If we do this correctly, we will have a complete view of every single play, for every single player, for every single game in an entire NFL season.  This information will also include Next Gen Stats positional data for correlation. 


<br>
<br>



### <font color='maroon'>Enhanced Visualization Expectations:</font>
 - Final presentation will include a fully interactive view of all NFL players by weight, height, offense/defense, college attended, BMI, football position, including deeper views of the players via html link to their official NFL profile. This visualization will also allow a deeper view into player positional coordinates. 


<br>
<br>



### <font color='maroon'>Expected Visualization Tool Approaches:</font>
- Interactive Vizualization: 
  - Bokeh
  - Altair
  - Holoviews
- Static Visualization:
  - Seaborn
  - Matplotlib
  - ggplot 


<br>
<br>



### <font color='maroon'>Core Technical Tools:</font>
 - Jupyter Notebook
 - Apache Spark tie-in
 - Heroku [prototype](https://immense-eyrie-75566.herokuapp.com/)
 


<br>
<br>



### <font color='maroon'>Some resources that should help you in this process:</font>
 - We have put together a [sample CodaLab competition](https://github.com/bethard/semeval-codalab) that you can use as a starting point for your task’s competition: 
 - Example Competition on CodaLab for Emotion Intensity: [CodaLab site](https://competitions.codalab.org/competitions/16380), [Code](https://github.com/felipebravom/EmoInt/tree/master/codalab)
 - Example Competition on CodaLab for Clinical TempEval: [CodaLab site](https://competitions.codalab.org/competitions/15621), [Code](https://github.com/bethard/clinical-tempeval)
 - Post your questions and issues on CodaLab [here](https://github.com/codalab/codalab-competitions/issues)
   - Search first to see if a similar question has already been asked and answered.
   - You can also post your questions to the semeval-task-organizers@googlegroups.com mailing group where other task organizers and semeval organizers might be of help.


<br>
<br>


### <font color='maroon'>Important Notes:</font>
 - Experiment with the [testing version of Codalab](https://competitions-test.codalab.org/) before uploading an official competition.
 - Dolt
   - https://www.dolthub.com/docs/tutorials/installation/#doltpy
   - https://github.com/dolthub/dolthub-etl-jobs/tree/master/adhoc/nfl-play-by-play 
   - https://github.com/dolthub/dolthub-etl-jobs/blob/master/adhoc/nfl-play-by-play/import-play-by-play.py
 - Heroku
   - https://devcenter.heroku.com/articles/getting-started-with-python#set-up
   - [Getting Started](https://devcenter.heroku.com/articles/getting-started-with-python#define-a-procfile)


<br>
<br>


#### <font color='maroon'>CONTACT</font>
General questions should be directed to Tom Bresee at [email]<tbresee@umich.edu>



**Source:** [Milestone](https://tombresee.github.io/NFL/milestone)

