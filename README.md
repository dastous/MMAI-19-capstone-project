# MMAI-19-capstone-project
Initial work completed for a client : CannaConnect

# Canadabis Strains
Data From Kaggle website: https://www.kaggle.com/kingburrito666/cannabis-strains

# Content
strain name: Given name of strain
type of strain: indica, sativa, hybrid
rating: user ratings averaged
effects: different effects optained
taste: taste of smoke
description: backround, etc

# Acknowledgements
https://www.leafly.com/
https://www.leafly.ca

# Inspiration
Marijuana may get a bad rep in the media as far as the decriminalization debate goes, but its health benefits can no longer go unnoticed. With various studies linking long-term marijuana use to positive, health-related effects, there are more than just a few reasons to smoke some weed every day.
A study done by the Boston Medical Center and the Boston University of Medicine, examined 589 drug users—more than 8 out of 10 of whom were pot smokers. It determined that “weed aficionados” were no more likely to visit the doctor than non-drug users. If an increased risk of contracting ailments is what’s preventing you from smoking more weed, it looks like you’re in the clear!
One of the greatest medicinal benefits of marijuana is its pain relieving qualities, which make it especially effective for treating chronic pain. From menstruation cramps to nerve pain, as little as three puffs of bud a day can help provide the same relief as synthetic painkillers. Marijuana relieves pain by “changing the way the nerves function,” says Mark Ware, MD and assistant professor of anesthesia and family medicine at McGill University.
Studies have found that patients suffering from arthritis could benefit from marijuana use. This is because naturally occurring chemicals in cannabis work to activate pathways in the body that help fight off joint inflammation.

# What people have done so far:
Predicting Canabis Species:            https://www.kaggle.com/kabure/auto-ml-pipeline-predicting-cannabis-species
Canabis Interactive Analysis with NLP: https://www.kaggle.com/couyang/cannabis-interactive-analysis-with-nlp  #with R
Canabis Strain Type To Flavor/Effect:  https://www.kaggle.com/kingburrito666/cannabis-strain-type-to-flavor-effects
In summary, previous authors have tried to predict the Type from the Rating, Effect and Flavor  --> they achieve 62%

# My contributions:
Exploration and Visualization  --> numerical complete, could need more visualization (Bokeh, go)
Sentiment analysis on the description  --> done
Term frequency of Description --> done
TF-IDF of Description --> done
Bag of Words of Description  --> done, but could do more (create specific BoW)
Word Embedding  --> done, but could do more (create specific WE)
Topic analysis from Description (what are the predominant topics? number of topic) 
LSA --> done
LDA --> done
HDA --> wont do
Gensim --> done
Mallet -- wont do

# What can be done with this initial dataset?

From the Description can we predict the Strain --> No not enough data from each strains (1 description per strains only)
From the Description can we predict the Rating (regardless of the strain)?  --> done
From the Description can we predict the Type? --> 74%
From the Description can we predict the Effects?  --> done
From the Description can we predict the Flavors?  --> done
From the Sentiment can we predict the Rating --> done
Can we find Strain names/Type/Effect/Flavor in the Description (associations to make?)

# Things that I have tried or will try later:
BERT --> nope
Bokeh -->done
Go Bar  --> not yet
Get the optimum number of topics 
Get the perplexity --> done
Get the Log Likelihood --> done
Get the coherence --> done
pyLDAvis visualization --> done
PCA  --> done
t-SNE  --> nope
