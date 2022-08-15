# Topic modelling of Amazon earphone reviews.
In this project I have used Amazon earphone reviews dataset from Kaggle. It contains reviews of various brands of earohones. I have consider only one brand named 'boAt Rockerz 255' for topic modelling. There are total 5000 reviews of this brand.

The libraries used in this project are numpy, pandas, matplotlib, nltk, spacy, gensim, pyLDAvis etc.
I have used Latent Dirichlet Allocation (LDA) for topic modelling.

After creating the model we found the optimum number of topics having the highest coherence value. It was found that with number of topics equal to 3 we get the maximum coherence value of 0.588. Therefore I have finalised the number of topics to be 3 topics(Topic1, Topic2 and Topic3). Topic 1 is related to sound quality, bass, battery, price.Topic 2 is related to product, use, working, warranty etc. Topic 3 is related to call, connecivity, mic, music, audio,voice etc.

After that I have found the dominant topic for each of the reviews. This will help us to classify the reviews into different topics(3 topics in this case) easily.

