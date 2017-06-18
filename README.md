# Social-Media-Analysis-of-Polaris

This project is focussed on getting to know what people think of Polaris Industries. The initial thought was to know the people's sentiments on Polaris Industries' customer and vehicle service, vehicle experience, warranty terms etc. Also, this will help the company reaching out to users who talk negatively about Polaris and will help in finding out the negtive subject about Polaris.

Using Twitter Official API, we can extract tweets about specific keywords only for the previous seven days. The number of tweets about Polaris during the last seven days were very few and would not be useful for analysis. Similarly, the live stream extraction of tweets about Polaris would give only a few tweets for analysis.<br>

Text Analytics requires more instances than normal Analytics. Hence, we need to get old tweets. Took help from https://github.com/Jefferson-Henrique/GetOldTweets-python which mimicked the twitter search and fetched the tweets for time frames longer than 7 days.

## Steps
### Initial Cleaning of data
<li> Filter out tweets from <strong>handles</strong> which have the names 'Polaris','Jobs'</li>
<li> Filter out job tweets by removing tweets with words 'hiring','Jobs'</li>
<li> Filter out stock suggestion tweets by removing tweets with words 'rating','analysts','stock'</li>

### Transforming the data to do Text Analytics
<li> Remove punctuations, numbers, links from Tweets</li>

### Exploratory analysis
<li> To find out users who tweets about Polaris most</li>
<li> To find out months with most tweets and correlating with activites of Polaris that month</li>

### Analysis
#### Word cloud
To find the most important words
#### Sentiment Analysis
To find out users who talak negatively about Polaris so that the company can reach out to them
#### N-grams and wordtoVec
To find what people think about Polaris' service and other things
#### Topic modelling
To find out the most talked about topics in Social Media

## Findings
<li>Found information about specific vehicle models about which people are happy and also found models about which people are not so happy.</li> 

## Limitations
This is work in progress as this is an addendum
<li>Could not infer anything on what people think about Polaris' service, vehile experience and other factors. This is because, there were lot of spanish tweets, which cluttered our analysis.</li>

## Road ahead
<li>Need to filter non English language Tweets</li>
<li>Need to find a way to filter commercial Tweets which include vehicle-selling tweets from users, spare parts selling tweets from commercial establishments etc.</li>

