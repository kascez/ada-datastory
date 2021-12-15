# The (under)talked problem of Climate Change

<p align="center">
  <img src="https://www.itu.int/en/mediacentre/backgrounders/PublishingImages/climate-change-backgrounder.jpg" alt="Climate change"/>
</p>

## Introduction
*"We have a single mission: to protect and hand on the planet to the next generation."* - Francois Hollande

Climate change is a global issue with global repercussions. We read, see, hear every day about the potential ecological disaster we are facing.

We will try, through this study, to conclude if we can deny or not some prejudice about climate change. For example, what kind of people are concerned about climate change. Is it always the youngest or, perhaps, politicians from a left-wing party? 

It is believed that all people, regardless of their background, should have an impact when it comes to facing the problem of climate change. Our goal is to determine how different groups of people react to this threat. Even though a person's nationality, age, political party, etc. separates him or her from other people, the desire for a better tomorrow is why the differences should be left aside.

To understand who speaks and what is said about this topic in the media, we used Quotebank, an open corpus of quotations extracted from English news articles. Because of the size of the dataset, we were able to keep only quotations with "climate change" and "global warming" in them while still having enough quotes to work with (more than 100 000). This simple method allowed us to be sure that almost all the citations were about the right topic. This high number of quotes related to climate change and global warming in a data set of about 178 million quotes speakes about the importance of this topic and how it is necessary to address it in a suitable manner


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

## General opinion about climate change

Diving deeply into the analysis, we wanted to see if there is a common opinion expressed by speakers from certain regions.

**How island countries feel about climate change?**

From the dataset, we selected the climate change quotes from speakers that are from the followig island countries: Maldives, Jamaica, Cuba, Dominican Republic, The Bahamas, Barbados, Mauritius, Tuvalu, Madagascar, Sri Lanka, Indonesia, Haiti, Seychelles, and Iceland. Because of the water level rising and the fact of these countries being isolated from the continental parts, we had a reason to believe that they had strong opinions abouut climate change. By summarizing more than 1000 quotations from these countries, we have extracted the following quotes as the most important and most repeating:

> This is particularly important for us as a small island developing State, given that climate change persistently threatens our development and even our existence.

> I think it's this lack of strong international action that concerns us, and that's very much true in the area of climate change as well.

The island countries have proven their fear of climate change. They are the ones that have higher risk of being affected by water levels rising, tsunamis, and earthquakes. All these dangers could strike the island countries earlier if the whole planet does not react faster.

**Statements from the Baltic countries**

The Baltic countries have been very much involved in the battle agaings the climate change for several years. We can many activist, such as Greta Thunberg, fighting against this burning worldwide problem. Here we presented the summarized 1073 opinions about climate change, stated by people from Sweeden, Finland, Lathvia, Lithuania and Estonia. 

> The rapidly growing demands to improve sustainability and saving the environment are opportunities for Northeastern students to become a leading pioneer with realistic answers on how to reduce Global Warming and climate change in the next three to five years, rather than a seemingly unsolvable problem at this time.

> Climate change must now be regarded as one of the most significant challenges to people's health and well-being.

The warmer winters without snow, the climate of the Baltic countries is changing. Although these countries can be observed as developed and they fight against climate change, it is the rest of the world's actions that they are afraid of.

**And how does the situation look at the Balkans?**

For a not that developed part of Europe, we collected the opinions of speakers from Slovenia, Croatia, North Macedonia, Romania, Bulgaria, Bosnia and Herzegovina, Greece, Albania and Serbia. The 184 quotes from this region provided us with the following summarization.

> Today we are moving to address EU concerns in the area of migration, make sure that consumers are better protected when they choose insurance products, and deliver on the EU's commitment to fight climate change and improve air quality.

> We look forward to participating constructively in this consultation in the hope that a final set of guidelines, based on scientific evidence, can find a more appropriate balance between the concerns of those opposed to wind farms and the need to take action on climate change.

The Balkans are considered to have problems of different kind and they are not so much interested in the problem of climate change. Most lately, as they are being more and more included into European problems and focused towards the European Union, people from this region have given us strong statements that backs up their climate change concerns.

**... and in the countries of Eastern Europe?**

This part of Europe has also been seen as less-developed that the rest. Their heavy metal industries, gas production, and factories are great pollutors of the air and water, thus, they are an enemy that affects the climate change. Speakers from Russia, Poland, Slovakia, Czech Republic, Belarus, Moldova, Ukraine, and Hungary gave their opinions about climate change, so we used them to point out the main ideas. Some of them were:

> Our ability to personally address the issue of climate change will determine the quality of life for all people on the planet as well as economic growth and sustainable social development worldwide.

> It became clear that the climate is a complicated system and that, so far, the evidence presented for the need to 'fight' global warming was rather unfounded

**What are the beliefs in the land down under?**

By looking at more than 10000 quotes by speakers from Australia, we can see that climate change is a burning topic for the Aussies. Some of the main statements that were extracted from their quotes are:

> What we don't need is a government that won't act on climate change and won't allocate any new funds to protect the Reef.

> At the same time, the science is getting clearer and the impacts of climate change are starting to unfold before our eyes.

Australia is definitely one of the most impacted countries by climate change. We all have witnessed the wildifires that occured in this country in 2020 which was the result of very high temperatures.

**...And on the other side of the world, what do people from the USA say?**

The USA have proven to be one of the most active allies in the battle against climate change. Since the number of quotes made by speakers from the USA outnumbered every other country among our data, we drawn some of the most popular idea between them:

> We agree with the consensus of scientific experts who note that without drastic action from everyone -- governments, companies and all of us as individuals -- adapting to the impact of climate change in the future will be far more difficult and costly, taking a toll on our supply chains, our business, and more importantly, the lives of everyone involved.

**Is the climate change concerning the elderly population?**

Even though climate change and global warming was not so popular when our grandparents were young, we still want to summarize opinion of the speakers that have more than 80 years.

> We stand in solidarity with those most affected by climate change -- often the most poor and vulnerable -- and call for the next Government to urgently stop contributing to climate change, and play their part in creating a just world for future generations.

> I think in some ways the non-scientific message from this is that climate change, or climate sensitivity, is large enough to need action, but not so large that it's too late to do anything

We can see that the elderly have strong opinions about climate change and see the urge to fight it, as they want to leave the planet Earth a nice place to live for the next generations.

## Sentiment Analysis : How climate change is being perceived by the world 

Before going much deeper into climate denial, we can run a sentiment analysis so that we can figure out the global perception of climate change among people.

TO do so, we will use the library Afinn. Afinn is a Wordlist-based approach for sentiment analysis that gives a score to sentence. If the score is high then your sentence tends to be positive. If not, that means your sentence is negative. Considering this fact, we have categorized all the quotes into three main groups : POSITIVE, NEUTRAL AND NEGATIVE. The result that we find are quite interesting. Here is two examples of positive and negative thoughts about climate change.

<p align="center">
  <img src="https://github.com/kascez/ada-datastory/blob/main/images/positive5.PNG" height="150" />
</p>


<p align="center">
  <img src="https://github.com/kascez/ada-datastory/blob/main/images/negative5.PNG" height="150" />
</p>


First of all, let's focus on the evolution of the mentality through the years. 

<p align="center">
  <img src="https://github.com/kascez/ada-datastory/blob/main/images/yearsEvolution.PNG" height="300" />
</p>

As you can see in the photos below, no truth stands out of the analysis. In fact, what can be deduce is that we already knew that climate change was a real issue. Things started to be done before and then we can find some pretty good result leading to a stable quantity of positive over negative through the years : 
<p align="center">
  <img src="https://github.com/kascez/ada-datastory/blob/main/images/Capture.PNG" height="300" />
</p>

However, we can see that in 2019 we had a lot of quote about climate change but can we really analyse those data. Indeed, we can't know if it comes from QuoteBank or if it is a general fact. It goes the same with 2020, which had an very low amount of quote. 

What seems to be a good conclusion is that the ratio remains the same for each years. Why ? It might come from the fact that every time we find some good result in climate change, there is a downside which compensate the good things. The quantity of negative quote trully need to downsize, as we can see in the first example of negative quote, a lot of disaster are still happening. 

The question that can be asked now is to know wether it is the younger or not that are optimistic (positive) about climate change. For this we have done another bar plot that represent the quantity of negative or positive quote according to the age of the author by category. 

<p align="center">
  <img src="https://github.com/kascez/ada-datastory/blob/main/images/Capture1.PNG" height="300" />
  <img src="https://github.com/kascez/ada-datastory/blob/main/images/Capture2.PNG" height="300" />
</p>

Here, we can see quite a large difference within the categories. At first sight, we can say that the youth quantity (category 0-30yo) is not relevant for the simple fact that we are working on quote of reknowned people and few young people are really known by wikipedia. Nonetheless, we can deduce something very interesting from those graphs : The 31-45 are not very reprensented in this sentiment analysis but can we infer that they are not aware of climate change and/or they don't care ? Hell, No ! To go deeper in this analysis, one can do real statistic on enough unbiased random people. However, it seems that inside the famous people family the 31-45 people do not have a sharp opinion (3000 negative VS 4000 positive). 

Finally, the most interesting fact that stands out from those two graphs is the difference between the 46-65 and the 66+. In addition to the fact that they are well represented inside the famous people, the ration seems to be quite relevant indeed. With a 16000 positive quotes and 10000 negative ones, that-is-to-say a ratio of 1,6, the 46-65 are very much ahead of the 66+, with a ratio of 12000/13000 ~ 0,923, we can deduce that famous people that are still working are more concerned about climate change in a positive way (optimistic maybe?). One of the reason we can evoque is that people from those ages are still politicians or actors or journalists, etc and are really dealing with those kind of climate change problems. 

The final words for this section is that we can't be categorical over this dataset as it is really biased. 

## Who denies climate change?

Some people doubt the scientific consensus around climate change. It could be about the reality of warming, about the fact it is caused by humans, or about its effect on nature and humanity. Those persons have, of course, a high tendency not to take decisions in favor of reducing our greenhouse gas emissions. We wanted to know what were the age categories and the political parties that deny the most climate change in the media the five last years. 

To train a machine-learning algorithm to detect the quotes about global warming denial, we labeled manually around 1000 randomly chosen quotes from the dataset. On 962 citations, only 23 were labeled positively as climate change denial. Because of this small number, we decided to add 38 climate skepticism quotes from another dataset. That brought our labeled set to exactly 1000 quotes. 

To be able to train algorithms on the quotations, we tokenized them, removed the stop words, transformed them in term frequency-inverse document frequency (TF-IDF) matrix, and kept the 20 top "concepts" using singular value decomposition. We split the data between a train and a test set, and we trained multiple times several machine learning algorithms to see which one had the best results. We tried logistic regression, a random forest classifier, a K-nearest-neighbor classifier, and a linear neural network. Our results were not very good. The models we tried had some difficulties finding the climate change denial quotes. They missed a lot of them (poor recall). However, the precision was not so bad (between 0.5 and 1 depending on the model). To have better results, more quotes should have been labeled but we did not have the time to do it. To be able to compare climate change denial between two categories of population, precision is the most important because it is better to know that true climate skeptical quotes have been selected even if some have been missed. Because of that, we decided to keep the logistic regression model that had the most consistent high precision in our runs. Finally, we labeled automatically all the quotes of our dataset with this model. 


<p align="center">
  <img src="https://github.com/kascez/ada-datastory/blob/main/images/denial_age.png?raw=true" height="230" />
  <img src="https://github.com/kascez/ada-datastory/blob/main/images/denial_party.png?raw=true" height="230" />
</p>

With our automatically labeled data, we computed the percentage of climate change denial quotes in the different age categories and in the different US political parties. We see that people above 66 years deny a lot more climate change when they talk in the media than the other age categories. For the US political parties, the Republican party members seem to deny a lot more climate change than the Democrat party members. These results look coherent with their political lines. However, a small party, the Independence Party of America, seems to outperform the Republicans on denying global warming. 

## But, how different groups of people react to climate change?

**Experiment with matching the speakers from different region by their age**

We were further interested to see whether the age makes influence on what attitude do speakers have towards the climate change in different countries. In order to analyze the previously mentioned, we have conducted an observational study by taking the following age cathegories as observed covariate: 31-45, 46-65 and 66+. The study was done by making the comperison between following countries: Germany and France, Belgium and Indonesia, Finland and Chile. 

Firstly, we analysed the sentiment score distributions of countries in mentioned pairs and analyzed the number of people in all age categories. It could have been seen that category '46-55' outnumber the other two cathegories in Belgium, Indonesia and Finland, whereas in Chile the dominant cathegory is '66+'. After, we used logistic regression to estimate the propensity scorea for all points. Then we used the propensity score to match each speaker from the first country in the pair with exactly one speaker from the second country in the pair, by trying to maximize the similarity between matched speakers, which is captured by their propensity scores. Lastly, we compared the outcomes for two countries as well as distributions of sentiment scores, but now only for matched speakers.

Considering the first pair, we have opted for Germany and France, since they are the two most populated European countries, are similar when it comes to the development level. On the graph below, showing age distribution with respect to the number of quotes of speakers cominig from these two countries, it could be seen that there is a difference between them when it comes to the number of quotes stated by people of different age.

<p align="center">
  <img src="https://github.com/kascez/ada-datastory/blob/main/images/GF2.PNG" height="300" />
</p>

On the lefthand side it can be seen the sentiment score distribution before propensity score matching and of the righthand side is the distribution after the matching was performed.

<p align="center">
  <img src="https://github.com/kascez/ada-datastory/blob/main/images/GF1.png?raw=true" height="230" />
  <img src="https://github.com/kascez/ada-datastory/blob/main/images/GF3.png?raw=true" height="230" />
</p>

Secondly, having in mind the indisputable geographical, cultural and divelopmental 'distance',the second chosen pair was Belgium and Indonesia. First graph presented below is again showing the age distribution of the the speakers from these countries, followed by distribution of the sentiment scores before and after the matching was done, on the left and right side respectively.

<p align="center">
  <img src="https://github.com/kascez/ada-datastory/blob/main/images/BI2.PNG" height="300" />
</p>

<p align="center">
  <img src="https://github.com/kascez/ada-datastory/blob/main/images/BI1.png?raw=true" height="230" />
  <img src="https://github.com/kascez/ada-datastory/blob/main/images/BI3.png?raw=true" height="230" />
</p>

Motivated with analysing different cultures and the effect the environment has on the individual opinion, the last pair chosen of this part of the analysis was Chile-Finland. Following are the results.

<p align="center">
  <img src="https://github.com/kascez/ada-datastory/blob/main/images/FC2.PNG" height="300" />
</p>

<p align="center">
  <img src="https://github.com/kascez/ada-datastory/blob/main/images/FC1.png?raw=true" height="230" />
  <img src="https://github.com/kascez/ada-datastory/blob/main/images/FC3.png?raw=true" height="230" />
</p>

Finally, it turned out that after the propensity score matching, in cases of all country pairs, distribution of sentiment scores had changed just slightly, telling that the observed covariate age does not have influence on what opinion people have on climate change.

**Have the right-wing and left-wing parties different opinions about climate change?**

Although right-wing and left-wing parties oppose each other in different categories, we wanted to check if there is a possibility that their opinions agree in terms of world-wide problems with a high risk - such as climate change. As the speakers from differently winged parties have different backgrounds, we have a reason to believe that there feelings about climate change would differ. 

To be able to conduct this experiment and check whether we can not distinguish between parties' quotes, we chose Germany to be our country for the example. We classified more than 20 parties from Germany into three groups: the right-center party, the left-center party, and the undefined parties or the parties which wing could not be easily determined. In total, we had about 1000 quotes which will be used to train our fasttext classifying model. After preprocessing the text, we prepared the quotes for the classifying. The results for all three groups can be observed in the following table:

|              	| precision 	| recall 	| F1-score 	|
|--------------	|-----------	|--------	|----------	|
| left-center  	| 0.333     	| 0.259  	| 0.291    	|
| right-center 	| 0.434     	| 0.655  	| 0.522    	|
| undefined    	| 0.263     	| 0.113  	| 0.158    	|

With the imbalance that we have in our data, we decided to focus on precision, recall, and F1-score for testing our claim. In the table above we can observe pretty much bad classifying results with most of the evaluation metrics being below 0.5. Personally, these results make us happy. By letting a very strong model perform this task and obtaining such bad results, we can say that it had a very hard time distinguishing between quotes from speakers that belong to a certain type of political party. We can say that there is a high chance that the speakers agree in terms of climate change, and that their quotes are similar. 

This analysis prove the equality that political parties have when battling big threats, and climate change is, undoubtedly, one of them.

## Is climate change receiving the attention it deserves?

Throughout this analysis, we proved the great media attention that climate change holds down. No matter the age you are, the region you are from, or the political party you choose to be in, one thing is certain - climate change is happening and it is our job to address it in a serious manner. Even though a speaker from our dataset has different beliefs than the rest, we can see that his opinion about global warming does not vary much from other speakers. 
