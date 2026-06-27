# Comparative analysis of news about the Russia's war of aggression against Ukraine in Ukrainian and international media using NLP methods.

### Overview
Russia’s full-scale invasion of Ukraine, which began in February 2022, has become one of the most widely covered events in the media space, both locally and globally. A huge amount of news is published daily and is growing rapidly as a result of the global information age. At the same time, the question arises: how do different publications cover events in Ukraine? Carrying out a comparative analysis is of important not only academic, but also strategic importance for understanding information influence and shaping public opinion.

### Chosen media
There were selected 8 news sources, 3 of which are Ukrainian. International media include famous outlets from  USA, Germany, Britain and Italy. This mix covers different languages and audiences making comparison meaningful and more rich.

### General framework of research
1. Data collection using web scraping
2. Data preprocessing and preparation
3. Media selection
4. Transformer-based Topic modeling and Named entity recognition
5. Implementation of analytical dashboard
6. Analysis of results and conclusions

The thesis consists of four main components: data collection, data preparation, NLP implementation, and dashboard development. Due to the scope of each stage, this repository highlights the most relevant part: the results of the news analysis presented via the dashboard.

### Methods and technologies used
1. Beautifulsoup4, Selenium, Playwright are used for web scraping.
2. BERTopic as a primary model for Topic modeling.
3. Multilingual-MiniLM-L12-v2 as an embedding model to create embeddings that were used in topic modeling, and also to explore semantic similarity.
4. XLM-RoBERTa-UK and BERT-BASE-NER for Named Entity Recogntition
Streamlit for dashboard implementation

### Dashboard
To make the analysis interpretable, an interactive dashboard was implemented. It provides a comprehensive cross-source view of how major Ukrainian and international media frame the war. 

The first part of dashboard is exploratory data analysis of news texts. In this section there were given answers to some questions.
1. KPI metrics: how many news were used for the analysis, number of languages, news data range and number of media sources.
![kpis](images/kpi_metrics.png)
2. It is also possible to check news publication dynamics over time, what periods are the most rich in news, what is the language and media distribution of news and some more.
![2](images/news_dynamics_over_time.png)
![3](images/top_months.png)
![4](images/media_and_lang_distribution.png)

### Conclusions

