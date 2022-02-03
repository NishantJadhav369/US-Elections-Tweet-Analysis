# US-Elections-Tweet-Analysis

Our project focused on the one of the most important political events in recent years, the 2020 United States election. We focused on a window of time where a lot of voters cast their vote, October 15th – October 31st. During this timeframe we observed tweets to see if the tweets had any correlation with the result of the election. With Donald Trump being one of the candidates and a prolific figure on Twitter (At the time) it ignited a thought within the group. Does twitter carry an impact on the United States Election?

We aimed to answer questions that would help layout what took place during the 2020 Election. One of our questions focused on the average sentiment on twitter for every state and how it reflects upon the results. This question allows us to focus on the potential correlation between tweets and winners of the state. This led us to dive deeper with the question did the sentiment of tweets change following a big event on a certain date (town hall meetings, debate, etc.) With this in mind, we proceeded to investigate what was the sentiment change due to the major event (from question 2) driven by a sentiment change in a certain state, this allowed us to answer the previous question better and see the specific change of states.

The story we extracted from the data was very insightful towards the nations view on the 2020 U.S Election. This insight can be profound for campaigns, news providers, data companies, and political organizations. This insight can allow companies and organizations to have a better feel for the pulse of the political atmosphere in the nation as it will affect everything from the economy, workforce, markets, and upcoming policy. Specifically, political campaigns and organizations can better understand what drives sentiment to swing and what they can do in the future to better help themselves.

We acquired two large data sets from Kaggle (https://www.kaggle.com/manchunhui/us-election-2020-tweets) that are compiled of scraped tweets from the time window October 15th – November 8th. One of the datasets focused of tweets related to Donald Trump, containing 970,919 rows and 21 columns. The other datasets contain tweets focused on Joe Biden has 776,886 rows and the same 21 columns. We also created a data set of the winner from the election in each state by acquiring data from CNN (https://www.cnn.com/election/2020/results/president). This was used in combination with the other two data sets to complete our analyses. We processed and cleaned a large amount of nominal/character data that through various techniques.Our processing allowed us to better understand the story the data/tweets were telling.

# Enlightening Findings:
## 1) Joe Biden vs Donald Trump Winner Prediction Map
<img width="1388" alt="USmap" src="https://user-images.githubusercontent.com/35873124/152046353-6ee41f4d-b098-455c-9fc7-c45e8080cb42.png">
 
## 2) Impact of events on sentiment change 
<img width="1420" alt="USline" src="https://user-images.githubusercontent.com/35873124/152046386-32926feb-be9c-47f0-a189-a52073f46f53.png">

## 3) Investigating the cause of major change in Florida
<img width="1420" alt="USbar" src="https://user-images.githubusercontent.com/35873124/152046400-f2c41e20-9e7f-44bf-aa40-d816897dbd36.png">

Based on the graph above, we see a significant swing in sentiment for anti-Biden Floridians. It can be inferred, that the "Florida Email scandal" had an impact on this. Floridians received emails being threatened to vote for Trump or "we are coming after you". The FBI had strong reason to believe that it was either Iranian or Russian collusion trying to affect the election results by tarnishing Trump. Because of this, many people believe that foreign powers that we have hostile relations with, like Iran and Russia, favor Biden over Trump. During the presential debate, trump was asked about the emails and his repone was along the lines of Russia and the middle east does not want him in power, so they are colluding to have Biden win. Florida Sen. Marco Rubio added to the fire as he is a Trump favoring republican and further added to the notion that trump is being discredit by foreign powers.

https://www.tampabay.com/news/florida-politics/elections/2020/10/23/the-florida-emails-came-up-in-the-debate-biden-and-trump-disagreed-on-those-too/

# Conclusion

This insight using twitter to track public sentiment can be extremly useful to many industries including campaign managers, lobbyists, Fortune 500 Companies, tax professionals, and other politicians as well. Using smiliar models steakholders can track sentiment around specific events whether its helping correlate public opinion on a certian stock, a specific bill in congress, a political movement like BLM, the posiibilities are endless.



