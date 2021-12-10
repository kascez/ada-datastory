# The (under)talked problem of Climate Change

<p align="center">
  <img src="https://www.itu.int/en/mediacentre/backgrounders/PublishingImages/climate-change-backgrounder.jpg" alt="Climate change"/>
</p>

## Introduction
*"We have a single mission: to protect and hand on the planet to the next generation."* - Francois Hollande

Climate change is a global issue with global repercussions. We read, see, hear every day about the potential ecological disaster we are facing.

We will try, through this study, to conclude if we can deny or not some prejudice about climate change. For example, what kind of people are concerned about climate change. Is it always the youngest or, perhaps, politicians from a left-wing party? 

It is believed that all people, regardless of their background, should have an impact when it comes to facing the problem of climate change. Our goal is to determine how different groups of people react to this threat. Even though a person's nationality, age, political party, etc. separates him or her from other people, the desire for a better tomorrow is why the differences should be left aside.

To understand who speaks and what is said about this topic in the media, we used Quotebank, an open corpus of quotations extracted from English news articles. Because of the size of the dataset, we were able to keep only quotations with "climate change" and "global warming" in them while still having enough quotes to work with (more than 100 000). This simple method allowed us to be sure that almost all the citations were about the right topic. 


> Insert a quote like this

<p align="center">
  <img src="https://github.com/kascez/ada-datastory/blob/main/images/people.png?raw=true" />
  <figcaption>This is my caption text.</figcaption>
</p>

## Research questions

1. What political parties have talked the most about climate change in the media?
2. Can we make a statement about the diversity between left-wing, center, and right-wing parties' quotes about climate change?
3. Does the age of the speaker cause a difference in the attitude and concerns one has about climate change?
4. How is climate change discussed among people of different nationalities all around the globe?
5. Do people from one region of the world have different opinions about climate change than the ones from other regions?
6. What are the biggest concerns about climate change in the world as shown in the media?
7. Do different groups of people (based on their age, nationality, and political party) have positive, neutral, or negative statements about climate change?

## Who talks about climate change?

We worked with data from 2015 to 2020. Our first analysis was to understand how the interest in global warming evolved through time in the media. To do this, we counted the number of quotes each year in our climate change dataset and in the general dataset to compute the percentage of quotes about the topic. You can see below the results we get. 

<p align="center">
  <img src="https://github.com/kascez/ada-datastory/blob/main/images/quotation_year.png?raw=true" width="350" />
</p>

It's interesting to see that it was stable between 2015 and 2018 but suddenly, the interest in this topic doubled in 2019. This could be explained by the movement launched around Greta Thunberg this year. With the COVID-19 pandemic in 2020, we could have thought that the subject became a lot less talked about, but we see that it is not the case. 

To know who were the people that talked the most about global warming in the media, we count the number of quotes per speaker. The top 3 speakers are the US president Barack Obama, the US politician Bernie Sanders, and the Indian prime minister Narendra Modi. We illustrate the top 20 speakers by a cloud of words. 

<p align="center">
  <img src="https://github.com/kascez/ada-datastory/blob/main/images/wordcloud.png?raw=true" width="400" />
</p>

Then, we asked ourselves where these quotations came from. To do this, we linked all the speakers of our global warming dataset to their nationality, thanks to Wikidata. The large majority of quotes come from the United States of America but there are also a lot of quotes from the United Kingdom, Canada, and Australia. That is what we expected because the data come from English news articles. However, we also have a few thousand quotes from big countries (China and India) and influential European countries like Germany and France. You can see below a map to quickly visualize where our citations come from. 

<p align="center">
  <img src="https://github.com/kascez/ada-datastory/blob/main/images/map.png?raw=true" width="700" />
</p>

Thanks to Wikidata, we also have information about the age and the political party of the speaker. The age categories the most represented are the 46-56 years old and the 66+ years old. For the political parties, the country the most interesting to analyze is the United States because it is the country with the most data. No surprise, the Democratic and the Republican parties, the two main American parties, have the most quotes about climate change in the media. However, it is interesting to note that the Democrats have two times more quotes about the topic than Republicans. 

<p align="center">
  <img src="https://github.com/kascez/ada-datastory/blob/main/images/age.png?raw=true" height="230" />
  <img src="https://github.com/kascez/ada-datastory/blob/main/images/party.png?raw=true" height="230" />
</p>

## General opinion about climate change (Text Summarization part)

## But, how different groups of people react to climate change?

## Sentiment Analysis : How climate change is being perceived by the world 

Before going much deeper into climate denial, we can run a sentiment analysis so that we can figure out the global perception of climate change among people.

TO do so, we will use the library Afinn

## Who denies climate change?

Some people doubt the scientific consensus around climate change. It could be about the reality of warming, about the fact it is caused by humans, or about its effect on nature and humanity. Those persons have, of course, a high tendency not to take decisions in favor of reducing our greenhouse gas emissions. We wanted to know what were the age categories and the political parties that deny the most climate change in the media the five last years. 

To train a machine-learning algorithm to detect the quotes about global warming denial, we labeled manually around 1000 randomly chosen quotes from the dataset. On 962 citations, only 23 were labeled positively as climate change denial. Because of this small number, we decided to add 38 climate skepticism quotes from another dataset. That brought our labeled set to exactly 1000 quotes. 

To be able to train algorithms on the quotations, we tokenized them, removed the stop words, transformed them in term frequency-inverse document frequency (TF-IDF) matrix, and kept the 20 top "concepts" using singular value decomposition. We split the data between a train and a test set, and we trained multiple times several machine learning algorithms to see which one had the best results. We tried logistic regression, a random forest classifier, a K-nearest-neighbor classifier, and a linear neural network. Our results were not very good. The models we tried had some difficulties finding the climate change denial quotes. They missed a lot of them (poor recall). However, the precision was not so bad (between 0.5 and 1 depending on the model). To have better results, more quotes should have been labeled but we did not have the time to do it. To be able to compare climate change denial between two categories of population, precision is the most important because it is better to know that true climate skeptical quotes have been selected even if some have been missed. Because of that, we decided to keep the logistic regression model that had the most consistent high precision in our runs. Finally, we labeled automatically all the quotes of our dataset with this model. 


<p align="center">
  <img src="https://github.com/kascez/ada-datastory/blob/main/images/denial_age.png?raw=true" height="230" />
  <img src="https://github.com/kascez/ada-datastory/blob/main/images/denial_party.png?raw=true" height="230" />
</p>

With our automatically labeled data, we computed the percentage of climate change denial quotes in the different age categories and in the different US political parties. We see that people above 66 years deny a lot more climate change when they talk in the media than the other age categories. For the US political parties, the Republican party members seem to deny a lot more climate change than the Democrat party members. These results look coherent with their political lines. However, a small party, the Independence Party of America, seems to outperform the Republicans on denying global warming. 
