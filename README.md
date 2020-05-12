# Covid Twitter visualization with Plotly
Visualizing Covid Twitter data using **Plotly**.
- Click on the link for a full visualization. You can use dropdown menu to view data in log/linear scale, use slider to find go through each date, click on the menu on the right side to remove keywords/hashtags not of your interest, and hover on the line/bar to see the exact value of counts. The page might take a few second to load. 

## Covid19 datasets: (Tweets were collected using covid19 related hashtags)
### Exploring hashtags and mentions over time 
Using sliders to see change of mentions and hashtags over time. These were the top 5 mentions and hashtag for each date during this collecting period. I tried to sort the keyword (hashtag or mention) by the total number of counts for the entire period, so for a particular day, the bar will not be all in descending order. 
- [Covid_top_hashtag_over_time](https://2miatran.github.io/twitter_visualization/Covid_hashtag_bar_over_time.html)
- [Covid_top_mention_over_time](https://2miatran.github.io/twitter_visualization/Covid_Mention_bar_over_time.html)
### Exploring the proportion of tweets that are retweeted, devices used to post tweets, language, location of user, location of original poster for retweeted tweets ...
- [Covid_Feature_Distribution](https://2miatran.github.io/twitter_visualization/Covid_Feature_Distribution.html)

## Actions datasets: (Tweets were collected using keywords/hashtags related to actions/measures). Total tweets: 5551925
### Exploring hashtags and mentions over time (These were the top 5 mentions and hashtag for each date during this collecting period)
Using **sliders** to see change of mentions and hashtags over time. 
Using **dropdown** to change linear scale or log scale
The "nan" is attributable to counts of tweets with no hashtags. These tweets are not collected based on hashtags, but based on the phrase "get tested". 
- [Top_hashtag_over_time](https://2miatran.github.io/twitter_visualization/Action_Hashtag_bar_over_time.html)
- [Top_mention_over_time](https://2miatran.github.io/twitter_visualization/Action_Mention_bar_over_time.html)

We also are interested in keyword action specific, which can be explored here. 
- [Action_hashtag_over_time](https://2miatran.github.io/twitter_visualization/Action_KeyWord_of_interest_specific_to_action.html)
- [Action_KeyWord_of_interest_specific_to_action_lineplot](https://2miatran.github.io/twitter_visualization/Action_KeyWord_of_interest_specific_to_action_lineplot.html)
- Here's a snippet
- ![image](https://github.com/2miatran/twitter_visualization/blob/master/slider_dropdown_menu_covid_action.png)
- ![image](https://github.com/2miatran/twitter_visualization/blob/master/Action_KeyWord_of_interest_specific_to_action_lineplot.png)

## Racism datasets: (Tweets were collected using keywords/hashtags related to [#iamnotavirus #hateisavirus])
### Exploring hashtags and mentions over time (These were the top 5 mentions and hashtag for each date during this collecting period)
- [Racism_top_hashtag_over_time](https://2miatran.github.io/twitter_visualization/Racism_Hashtag_over_time_lineplot.html)
- Here's a snippet
- ![image](https://github.com/2miatran/twitter_visualization/blob/master/Racism_Hashtag_over_time_lineplot.png)


