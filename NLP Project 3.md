# Executive Summary:

Over the last few, it seems we are inundated with news articles that sound like they belong in an alternative universe. It seems that recently many news articles are starting to sound more like The Onion articles every day. While this is probably more concerning than funny, I want to set out to see if I can train a model to be able to predict the difference.

I am particularly interested in the validity of this statement. Do real news articles honestly sound like Onion Articles? Particularly those that read like The Onion articles. The evidence is mostly anecdotal, but it would be interesting to see if there are key words or phrases that are more associated with Onion articles versus real articles.

Luckily, there is a way we can test this! Using Natural Language Processing, we can try to structure words in such a way that a computer can understand, model, and predict.

To test this hypothesis, I gathered data from subreddits r/TheOnion and
r/nottheonion. The second subreddit posts actual news articles that sound unreal. This subreddit is the closest I can get to one place where the types of articles I’m looking for can be compared and trained against The Onion articles. Indeed, the description of r/nottheonion is “For true stories that are so mind-blowingly ridiculous, that you could have sworn it was an Onion Story”.

Without going too deep into the weeds, I would argue that the hypothesis supports the anecdotal evidence. I think that trying to train the computer to understand the difference between satire and a real news story, is quite difficult. While the model says it predicted the results with about 74% accuracy, the AUC/ROC curve visually shows us that there doesn't appear to be a whole lot of distinction between the positive and negative outcomes, and, in fact, most of my data seems to overlap. Additionally, there was significantly more data for The Onion than Not the Onion, meaning I had a really unbalanced model. 
