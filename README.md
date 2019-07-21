## Senior Pedestrians in NYC: A Diff-in-Diff Approach to Evaluating Safe Streets for Seniors
### Organization: New York Univeristy Center for Urban Science + Progress
### Sponsor: Daniela Hochfellner
### By Pengzi Li, Sam Burns, Po-Yang Kang, Asilayi Bahetibieke
-------------------------------------------------------------------------------------------
**Abstract**

Urban senior populations are expected to grow significantly in the coming decades. This demographic trend requires adjustments to policy and infrastructure in cities. New York City has implemented its Safe Streets for Seniors (SSfS) program, which includes identifying Senior Pedestrian Focus Areas (SPFAs) and making structural improvements designed to improve safety for senior pedestrians to address its aging population. This study investigates whether or not the established SPFAs improved safety for seniors. Using difference-in-difference estimators, we find that setting up SPFA zones in NYC leads to a decrease of about 34 percent in the number of seniors killed in motor vehicle accidents. The number of accidents involving senior pedestrians relative to non-SPFA zones decreased too, however only by 5 percent. Overall, our results show that New York City’s programs addressing senior citizens is successful  and suggest that other cities in the US and abroad should adopt transportation policies similar to NYC’s in order to protect senior citizens.

**URL of our website**:https://agingcapstone.github.io/ssfs/

----------------------------------------------------------------------------------------------
**Data**

Our diff-in-diff analysis relies primarily on two data sets - traffic fatality data collected from the National Highway Traffic Safety Administration (NHTSA) and SPFA spatial data from NYC DOT. The data can be download through the following links:

**NHTSA traffic fatality data**: ftp://ftp.nhtsa.dot.gov/fars/ 


**SPFA spatial data**: https://data.cityofnewyork.us/Transportation/VZV_Safe-Streets-for-Seniors/bsuh-ywiw
-----------------------------------------------------------------------------------------------
**Result**
![Alt_text](Results_and_Visualization/Main_Result.png)

-----------------------------------------------------------------------------------------------
**Content**

|Direction                                                 |Corresponding Notebooks                            |
|----------------------------------------------------------|---------------------------------------------------|
|**Data cleaning and wrangling**                           |1.1 personClean.ipynb                              |
|                                                          |1.2 accidentClean.ipynb                            |
|                                                          |2. mergeClean.ipynb                                |
|                                                          |3. spatialJoinnDescriptiveStats.ipynb              |
|**Reorganized dataset for linear regression model**       |4. CensusTractMerge.ipynb                          |
|**Linear regression model and robustness check**          |5.1 Linear_regression.ipynb                        |
|                                                          |5.2 LR_RobustnessCheck.ipynb                       |
|**Model visualization**                                   |6. Line_Plots_For_Final_Report.ipynb               |
|**Report (Previous progressive reports and final report)**|Report (folder)                                    |
|**Model results and graphs**                              |Results_and_Visualization (folder)                 |
