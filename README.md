# Preliminary Research: Why Visualize Competitive Code? Preliminary Categories for Jupyter Notebooks
> This is a preliminary research for the 29th Asia-Pacific Software Engineering Conference (APSEC 2022)  paper "**Why Visualize Competitive Code? Preliminary Categories for Jupyter Notebooks**".

## Abstract
Data visualization becomes a crucial component in data analytics, especially data exploration, understanding, and analysis. 
Effective data visualization impacts decision-making and aids in discovering and understanding relationships. It leads to benefits in data-intensive software development tasks e.g., feature engineering in machine learning-based software projects. 
However, it is unknown how visualizations are used in competitive programming.
The idea of this paper is to report early results on what visualizations are prevalent in competitive programming.
Grandmasters are the highest level reached in competitions (novice, expert, master, and grandmaster).
Analyzing the visualizations of 7 high-rank competitors (i.e., Grandmaster) in Kaggle, we identify and present a catalog of visualizations used to both tell a story from the data, as well as explain the process and pipelines involved to explain their coding solutions. 
Our taxonomy includes nine types from over 821 visualizations in 68 instances of Jupyter notebooks.
Furthermore, most visualizations are for data analysis for distribution (DA Distribution), and frequency (DA Frequency) are most used.
We envision that this catalog can be useful to better understand different situations in which to employ these visualizations.

## Background
### Kaggle
Kaggle is an online community platform for people who are interested in data science and machine learning. It allows users to collaborate and compete with others in data science competitions to solve challenges. The users' performances are ranked based on their contribution to four platforms which are:
- Competitions 
- Notebooks 
- Datasets
- Discussion.

The Kaggle progression system is used to determine competitor ranking which consists of 5 performance tiers:
- Novice
- Contributor
- Expert
- Master
- Grandmaster

**Target Competitor:** In this study, we focus on the **Notebook Grandmaster** tier achieving 15 notebook gold medals. Each medal is awarded to popular notebooks which are measured by the number of upvotes on those notebooks which require 50 votes. We selected to focus on notebook grandmasters because they mostly have data visualization in their notebooks for data exploration and can be ranked based on the upvotes of the notebooks.

## Categories of Visualizations
> The purposes of visualization can be catagorized into (1) Data analysis (DA) (2) Machine learning model interpretation (ML).
### Distribution DA
Showing the data distribution, the graph type in this category is a histogram, box plot, and violin plot.

![Distribution example](https://drive.google.com/uc?export=view&id=1tbnC0HLx73BXSSlO8ESGtLK8yxpJgJiR)

### Frequency DA
the visualization display the frequency of the data for data analysis with the graph type count plot, bar plot, and word cloud.

![Freq example](https://drive.google.com/uc?export=view&id=1zjqnZp0BlzNHcL477eoRHPnNk4cC8po_)

### Map DA
Displaying data on a geographical map to demonstrate the spatial relationships in data

![Map example](https://drive.google.com/uc?export=view&id=1uOT6jnrbL3AUNJx2FlvFQOm3DEqsBdgw)

### Percentage DA
the visualization that shows the percentage of data

![Percentage example](https://drive.google.com/uc?export=view&id=1gR_526mEswj2g8B0bjLIIc_RT51zf43v)

### Statistics DA
Visualizing statistics data with the keyword correlation and confusion matrix in the title.

![Stats example](https://drive.google.com/uc?export=view&id=17iKTGBq83KN4egCRYab5Tp5kCeNeUurw)

### Train Model ML
The visualizations that have a purpose for model interpretation in the training process e.g., the line graph shows the training accuracy.

![Train example](https://drive.google.com/uc?export=view&id=1uljr1GYlDpsys4CfaGBdqHLcag1I6_Gz)

### Test Model ML
The visualization that intends to show model interpretation or the result in the testing process containing submission or prediction as a keyword.

![Test example](https://drive.google.com/uc?export=view&id=1U-IbT9wGrJlrqxCig7xJ4WqgpQN4Bdr-)

### Image Model ML
The visualization that shows the image that is being used in the model.

![Image example](https://drive.google.com/uc?export=view&id=10fEye24SH96ZPQzF19BI1IiCPEFZhVwY)

### Feature Importance ML
Visualizing the feature importance of model

![Imp example](https://drive.google.com/uc?export=view&id=1dAo-QN4qnRhsCsliJvcBE_YdNbFtZpA9)

### Others
The visualization that cannot fall into any classification type

![Other example](https://drive.google.com/uc?export=view&id=1Pzm7zha0RJjs-QWsV9d477zYqjp74Ej2)

# Authors
- Tasha Settewong
- Natanon Ritta
- [Raula Gaikovina Kula](https://raux.github.io/)
- [Chaiyong Ragkhitwetsagul](https://cragkhit.github.io/)
- Thanwadee Sunetnanta
- [Kenichi Matsumoto](https://matsumotokenichi.github.io/)
