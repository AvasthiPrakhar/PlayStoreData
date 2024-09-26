# PlayStore Data Analysis to identify Ratings and Installation Metrics for maintenance of old and potentially introducing new apps.

Exploration and Analysis of Google Play store [Data](https://www.kaggle.com/datasets/gauthamp10/google-playstore-apps) Scrapped from the Google Play store in 2021 and contains Application data of more than 600K applications with 23 attributes.

Before Analysis, This data set has been cleaned and formatted. Python Scripts and insights specific to that phase can be found [here](https://github.com/AvasthiPrakhar/PlayStoreData/blob/main/DataCleaning.ipynb) 

A Tableau Story with Interactive Dashboards can be found [here (Story 1)](https://public.tableau.com/app/profile/prakhar.a3419/viz/Story1AnalysisofRatings/Story1) and [here (Story 2)](https://public.tableau.com/app/profile/prakhar.a3419/viz/Story2Installations/Story2)

![Story](https://github.com/user-attachments/assets/0c97b6ec-f261-4b95-8e7a-0d86ec5562fb)
![Story 2](https://github.com/user-attachments/assets/8aca17cc-1bae-4e66-aff1-58a79a361e47)


**Analysed Metrics :** 
  - **Rating** : Rating of an App
  - **Installs**: Number of Installations per app

**Summary  Insights**

  **Rating:**
  
  1. It was found that **46.28%** of the apps, that is, about **1,034,375**  out of a total of **2,235,250** Apps analysed on the Play Store have never been rated even once. This makes the probability of getting rated at least once to be about **54 %**
  2. Given an App is Rated at least once, Overall Mean Rating is found to be **4.10** out of 5 and the Overall Median is found to be **4.2** out of 5.
  3. Approximately **45%** of all the Apps have a rating of 3.5 and Above.
  4. For all apps, the rating distribution into brackets from 1 to 5 varies **non-uniformally**. Further, Each app 'Category' has its distribution of Ratings.
  5. **16** App Categories out of **47** such as 'Music and Audio',' Books & Reference' and more have an above average Rating distributed across approximately **600,000** apps.
  6. Rating Distributions and Propotion of not-rated apps (A Rating of 0.0) also vary based on revenue dimensions such as whether the App is Free or Paid, Whether the App Supports App purchases or not and Whether the App has Ad support.
  7. 0 rating App share varies **greatly** based on whether the app supports in-app purchase or not and based on whether the app supports ads or not, but does **not** vary as greatly based on whether the App is Free or Paid
  8. A final Rating distribution Dashboard has been provided to test and visualise Rating distributions cut in all specified dimensions.


**Installs**

1. About **53,842,610,600** Installations have been performed and distributed across all the apps. Whereas Mean Installations are **715,127, the Median stands as only **1,000** installations.
2. Top 3 installation brackets are **1000+** , **10,000+** and , **100+** repectively.
3. Based on Category Dimension, **'Tools'** category has had the highest share of installations at about **15 %**, second highest being 'Communication' at **10%**
4. Categories 'Events', 'Parenting' and 'Libraries and Demo' have the lowest installations at **0.02%**, **0.06%** and **0.10%** respectively.
5. For Paid Apps, when compared to Free App installations, installations **dwindle** drastically.
6. Share of Installations of Apps that do and do not support Ads varies **drastically** for each category. 
7. Share of Installations of Apps that do and do not support In-App purchases varies **drastically** for each category.
8. A summary of Apps that lie different potential revenue streams has been provided where it can be seen that Free Apps, with no ads and no in-app purchases, have the highest share at **960,157** Apps And, App that are Free and Do **not** support Ads but **do** Support In-App purchases have the second highest share at **662,504 Apps**.

**Recommendations:**
1. Existing Apps and Potential new Apps may introduce a feedback system based on some incentive or a prompt to the user. The budget and implementation for the same may be discussed with the Marketing and engineering team.
2. A potential new App can be introduced in one of 16 categories with a Higher or lower than mean rating segment based on risk appetite, budget and implementation as may be discussed and assessed by the Marketing and Engineering teams. 
3. Since Median App installations stand at a lower share, it may be advised to launch a marketing campaign to promote the App
4. A potential new app can be introduced in a category that has a higher installation share of installations based on which revenue stream can be decided 
5. Apps may keep In-App purchases as the main revenue stream for a higher installation share.


  
    
    
    
    
    



  
