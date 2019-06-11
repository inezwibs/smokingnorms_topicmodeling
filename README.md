# smokingnorms_topicmodeling
Research Internship, SFSU + UCSF partnership, Identify Smoking Norms in SF Bay Communities

The included Jupyter Notebook files provide a list of scripts used to 
1. Mine data from Reddit using Pushshift Reddit API to gather as many smoking results that match bigram queries on smoking related keywords
2. Topic modeling using Gensim library. The notebook provides a progression of the data cleaning process; i.e. removing stop words, 
lemmatizing, then building the lda model. We use pyLDAvis to help visualize the 10 topics requested.

Lastly the report provides background and analysis of the results. Of the data mined between the two months of Jan and Feb 2018,
the smoking norms topic modeling picked up smoking, vaping, and vaping mods topic. These could be potential new queries for 
future topic models. 

