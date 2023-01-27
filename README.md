# This Side of Paradise
An analysis of architects' salary while I'm preparing for interview

***🔨 Under Construction Now 🏗️***

I make this repo public to be accountable, hence it will be a hot mess for one week or so :)
 
## Repo name origin
"This Side of Paradise" is a novel by American writer F. Scott Fitzgerald, a major theme in which is the **disillusionment** one feels as one grows in his college years. 

This theme properly describes a lots of architects' feelings when they find the disillusionment between their salary and once aspiration, me included, two years ago.

## Aims
1. Find insights and patterns of architects' salary.
2. Revisit statistics knowledge in practice.
3. Illustrate why I'm leaving architecture/ urban planning industry.

## Note
Definition of architects here: includes landscape architects, urban designers, and urban planners, etc. Because (at least in China) these majors are all under the architecture category in universities.

## Data source
1. A shared excel file, architects inputting their salary-related information anonymously.
> The original data is not MIT License and I don't own the right to commit it in this repo. 
If you are interested in this data, please directly contact WeChat Official Acount [建筑透明性](https://mp.weixin.qq.com/s/AEFNmtd_lDZpfYhcI2PkAA) at the bottom of this blog.

2. cn_stopwords.txt (Chinese stopwords in the NLP part) -  goto456.2020.stopwords.https://github.com/goto456/stopwords/

3. centroids.md (Chinese province centroids in the interactive map part) - siliushi.2015.geocoord.https://github.com/siliushi/geocoord


## Techniques used

data wrangling: Python - Pandas, Re(Regular Expression)

EDA: R, Python - Pandas

statistical model(multivariate regression): R

machine learning(NLP with TF-IDF and K-means): Python - scikit-learn

data visualization: Python - Folium, Matplotlib, Wordcloud

## Estimate output

- final output
1. multivariate regression analysis, answering the question "what factor most influences architects' salary?"

2. cluster analysis of comments, answering the question "what are major salary-related topics architects talking about?"

3. good old web map, answering the question "how do architects' location distributed?"

- process output
1. structured salary data(not committed)





