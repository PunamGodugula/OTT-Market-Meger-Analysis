# 🎬 OTT Platforms Merger Analysis 

This repository contains resources for merger analyzing of two OTT platforms LioCinema and Jotstar

- 🛠️ **Python** for data extraction and [Primary Analysis](https://github.com/PunamGodugula/OTT-Merger/tree/main/Python%20files)
- 📊 **Dashboards** showcasing visual insights. [Dashboard files](https://github.com/PunamGodugula/OTT-Merger/tree/main/PowerBI%20Dashboard), [Live Dashborad](https://app.powerbi.com/view?r=eyJrIjoiOTQ2MjNiOTAtMTYzYy00YTNmLWEyYzAtM2M2NTNmOGMxOTM5IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9&pageName=66003f1609d930b3aabc)
- 📑 **Presentations** with actionable recommendations for merger.  

## 📝 Introduction  
Lio, a leading telecommunications provider in India, is planning a strategic merger with Jotstar, one of the country’s most prominent streaming platforms.

### Vision:  
To make the merged platform as leading OTT platform with divered content and massive user growth.

## ⚠️ Problem Statement  
 To make the merger sucessful, Lio Management needs to look at the detailed analysis on:

- Content Library Analysis 
- Subscriber Insights
- Inactivity Analysis
- Upgrade Patterns
- Downgrade Patterns
- Content Consumption Behavior

## 🎯 Objective  
- Analyze SQL databases to address key **Business Questions** on Content library, Subscribers behavior, Subscription Plans, Content Viewing Behavior and Revenue.  
- Present findings in a clear and visually engaging manner to assist Lio Management in making informed strategic decisions.  

## 👩‍💻 Tech Stack  
- **Data Visualization:** Power BI  
- **Data Analysis:** Python  
- **Data Modeling:** Snowflake schema  
- **Tools:**  SQL, Power BI Desktop, Power BI Service, and PowerPoint.

## 🫙Data Overview :
Received two SQL databases one for LioCinema and another for Jotstar for the analysis, the tables present in each of the databases are of similar structure.
The tables are :
1. Content : This table provides detailed information about the content available on the platform, enabling analysis of content diversity, genre popularity, and runtime patterns.
2. Subscribers : This table captures demographic and subscription details for users, enabling insights into subscriber acquisition, upgrades, downgrades, and inactivity patterns.
3. Content Consumption :  This table captures user-level content consumption data, enabling analysis of total watch time, device preferences, and engagement trends

Download files and explore more on this project here : [link](https://codebasics.io/challenge/codebasics-resume-project-challenge#uploadSuccess17)

## 🗝️ Key Insights : 
### Content Library Analysis :
  - **Liocinema** : 35% share of total library content, less diverse content, Movie-centric, stronger regional presence
  - **Jotstar** : 65% share of total library, more diverse languages, genre and contents.

### Subscribers Insights :
- **LioCinema** : 80% share, exponential user growth,
- **Jotstar** : 20% share, linear user growth

## User Demographics : 
- **Liocinema** : Popular among Youth(18-24) with 44% of its users, popular in Tier-3 with 43%
- **Jotstar** : 45% of the users belong to Young Adults (25-34), 57% users belong to Tier-1.

## Inactivity Analysis :
- **Liocinema** : 39% of the users are inactive showing less content attactive with majority of them belong to Young adults(19%) and Free Subscription Plan
- **Jotstar** : 13% of users are inactive shows better rententeion of users.

## Upgrade Pattern : 
- **Liocinema** : Only 1.5% of users upgraded to plan, with 50% of users upgraded to basic plan and 50% to premium plan
- **Jotstar** : 9.1% of users upgraded their plan, with 81% of users upgraded to Premium plans shows people enjoy the content.

## Downgrade Pattern : 
- **Liocinema** : 9.7% users downgraded their plan, with 85% of users downgraded to Free plan 
- **Jotstar** : 4.7% of users downgraded their plan, with 87% of users upgraded to Free plan.

## Content Consumption Behavior : 
- **Liocinema** : ARPU is 60 hours, mobile viewing dominated among devices, weak enagement across al city-tiers.
- **Jotstar** : ARPU is 352 hours, mobile viewing dominated but good enagement all other devices, higher enagement across all tiers with ARPU > 250 hours

  


  
