# sentiment-analysis
Ways to analysis the reaction of peoples on some real time topic.
Here we are going to use twitter psychlogical data(thousands of reactions and opinion on every topic) by that we can predict the sentiment on any random topic.showing what is reaction of peoples on that topic.
**analysis part takes input text like a tweet and split it up into tokens(serval words and sentences)**
Every word have thier own sentiment value(pre-difined in python library) also know as sentiment lexicon.
 
 
 **steps for implementing project**
first->registor for twitter API
second->install dependencies
finally->Write our script

**example**->
>>wiki=TextBlob("manish is worst in cheating")
wiki.tags=[['manish','NNP'],['is','VBZ'],['worst','jj'],['in','IN']]
>>wiki.sentiment.polarity
-0.5002
