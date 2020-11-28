---
title: Milestone
---


## Milestone - University of Michigan

|

### Project: NFL-Eval

Creating an extended EDA template for NFL football stats.  This will also entail API connectivity for multiple data sources.  Endgoal is.  

Evaluation of complex data plays. 


|


### Core Raw Data Sources:
 - [NFL Kaggle 2021 Repo](https://www.kaggle.com/c/nfl-big-data-bowl-2021/data)
   - 20 separate files (including one with 18M samples), and 363 columns
   - Total Set Size:  2.17 GB
   - Accessible via kaggle API python node 

 - [NFL Kaggle 2020 Repo](https://www.kaggle.com/c/nfl-big-data-bowl-2020/data)
   - Total Set Size:  276.47 MB
   - Accessible via kaggle API python node 

 - [NFL Next Gen Stats](https://nextgenstats.nfl.com/)

 - [NFL Play by Play Data](https://www.dolthub.com/repositories/Liquidata/nfl-play-by-play)
   - This data sourced from original nflfastR package scrape of this: https://github.com/guga31bb/nflfastR-data

 - [Shield](https://api.nfl.com/docs/getting-started/index.html)
   - Shield represents the client-facing API that will serve the needs of internal projects, external contributors, third-parties and fans alike. It is the primary way to read and write content to the NFL. It will allow users to find content, submit content for use in client applications and websites.
  - [API Endpoints](https://api.nfl.com/docs/global/endpoints/index.html) 
    - This is a full list of the available Shield API root nodes.



|



### Expected Data Manipulation:
 - Initial Processing:
   - Expected 
- Merging:
   - Expected is 
- New information resulted from combining them:
   - abc 


|



### Enhanced Visualization Expectations:
 - Initial Processing:



|



### Expected Visualization Tool Approaches:
 - Interactive Vizualization: 
   - Bokeh
   - Altair
   - Holoviews
 - Static Visualization:
   - Seaborn
   - Matplotlib
   - ggplot 


|


### Core Technical Tools:
 - Jupyter Notebook
 - Apache Spark tie-in
 - 


|



### Some resources that should help you in this process:
 - We have put together a [sample CodaLab competition](https://github.com/bethard/semeval-codalab) that you can use as a starting point for your task’s competition: 
 - Example Competition on CodaLab for Emotion Intensity: [CodaLab site](https://competitions.codalab.org/competitions/16380), [Code](https://github.com/felipebravom/EmoInt/tree/master/codalab)
 - Example Competition on CodaLab for Clinical TempEval: [CodaLab site](https://competitions.codalab.org/competitions/15621), [Code](https://github.com/bethard/clinical-tempeval)
 - Post your questions and issues on CodaLab [here](https://github.com/codalab/codalab-competitions/issues)
   - Search first to see if a similar question has already been asked and answered.
   - You can also post your questions to the semeval-task-organizers@googlegroups.com mailing group where other task organizers and semeval organizers might be of help.


|


### Important Notes:
 - Experiment with the [testing version of Codalab](https://competitions-test.codalab.org/) before uploading an official competition.
 - Create only a single CodaLab competition, even if you have multiple subtasks. Multiple CodaLab competitions solve very few problems and make things more complicated.
   - If you have multiple subtasks, define a submission file format that is the same regardless of how many subtasks someone participants in.
   - If you have multiple subtasks, your evaluation script will have to handle cases where a participant makes submissions for only one or some subtasks.
 - Ensure that your CodaLab competition defines a detailed `overview.html`, `data.html`, and `evaluation.html`. These are the key pieces of documentation for your task, and they're what potential participants will be looking at.
 - While the CodaLab browser-based interface can update many parts of a competition, there are several known circumstances where the only way to modify part of a CodaLab competition is to delete and recreate it, uploading a new `competition.yaml`, etc. Some such circumstances are:
   - Adding or removing `.html` files from the CodaLab website
   - Modifying the leaderboard (e.g., adding new evaluation metrics)
   - Adding a new phase (if done via the browser-based interface, leaderboards will not display)
 - Make sure your evaluation script throws errors (and exits with an error status) for all formatting issues you are able to detect in system submissions. This will ensure that ill-formatted submissions do not count against a participant’s submission limit.
   - A very common error is for participants to include an extra subdirectory in their submission. Please make sure your evaluation script detects and handles this error.
 



#### CONTACT
General questions should be directed to <tbresee@umich.edu>



**Source:** [Milestone](https://tombresee.github.io/NFL/milestone)

