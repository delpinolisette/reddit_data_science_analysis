## A Data Story from Reddit

In this repository, I present an analysis of social media behavior on Reddit career advice forums after the start of the coronavirus pandemic in the United States. 

Using the tools of data science and descriptive statistics, I construct an easy-to-interpret narrative on the change in activity of these forums after March 2020. [Link to Analysis](https://github.com/delpinolisette/reddit_data_science_analysis/blob/master/data_story_presentation/data_story.md)

Lisette del Pino
  
### Directory Tree Diagram:
```
├───data
│   ├───processed (monthly subreddit data in csv)
│   └───raw (all raw data)
├───data_analysis
│   └───scraping
│       ├─── jobs_scrape.py ( should be gitignored )
│       └─── Using PRAW to Scrape Data
└───data_story_presentation
│   ├───img (folder with figures)
│   └───data_story.md
│   └───data_story.pdf

```

- `data`: folder keeping track of both raw and cleaned up data sets. see its README for more info. 

- `data_analysis`: folder keeping track of analyses of all data sets. It has a *lot* of content, check it out!! see its README for more info. 
  - `data_analysis/scraping`: keeps track of python modules written to aid with scraping using PRAW and Reddit API. 

- `data_story_presentation`: final, finished data story readable from both markdown and pdf files. 



### Extra: What I've Learned:

- In this project, I learned:
    - how to use PRAW to scrape subreddits
    - how to store a secret key
    - how to create a csv from data frames, and vice versa
    - how to analyze large datasets and look for patterns
    - how to keep track of many moving parts in long-term project. 
    - how to present my findings using the visualization aids. 


### Project Management 

Since Github renders to do lists now, going to list my tasks here:

- [x] Scrape data for `CSCareerQuestions` subreddit and convert dates
- [x] Scrape data for newest `Jobs` data and convert dates
- [x] Scrape data for  `CareerGuidance` subreddit and convert dates
- [x] Scrape data for `ExperiencedDevs` subreddit and convert dates
- [x] Perform data analysis on jobs dataset 
  - [x] dimensions + subsetting by month + filter to highest comments + filter to average comment + median scores (to compare others to) + highlight the most important post from each month + highlight the most important post overall
- [x] Perform data analysis on careerguidance dataset
- [x] curate data story some more



