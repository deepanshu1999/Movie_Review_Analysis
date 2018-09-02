# Movie Sentiment Analysis
Using Natural Language Processing algorithms to analyse each and every movie review and judge whether the person liked the movie or not.
## Dataset
- #### Cardinality
   - Test Data: 25000
   - Training Data: 25000
 
 Dataset contains total 50000 text files arranged in different folders. Each text file has the review of a user in plain english.
Link: [ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz](ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz)
## Tech:
- [scikit-learn](http://scikit-learn.org/stable/) A free machine learning library for python
- [Natural Language Toolkit](https://www.nltk.org/) NLTK is a leading platform for building Python programs to work with human language data.
- [Python](www.python.org)

## Result
The model with accuracy of 70% correctly predicted movie reviews

>I was fortunate enough to see this movie on pre-release last night and, though I wasn't expecting to, actually really enjoyed the movie for the most part. The rescues and sea effects were amazing to watch and definitely provided edge of the seat tense moments, probably all the more so knowing that there are guys who do this for a living. The weaker parts of the movie revolve largely around using stereotypical set scenes. I'm not going to spoil the movie but this really follows along the lines of An Officer and a Gentleman and those moments give it a little bit of a cheesy aftertaste. Like I said over all this movie is pretty good and worth checking out as long as you can get past the clichés.

Prediction: Positive

>This movie made by the NFBC was made in honor of the Montreal Canadians dynasty years in the 50's,60's and 70's. My 5th grade teacher played this in class in honor of my 11th birthday in 1987 and also to celebrate my return from a serious facial injury in 1986. I have been a Canadians fan for 29 of my 30 years of life. on a scale of 1-10, I give this film a 117. All hockey fans should see this as I hope it will be placed in the Hockey Hall of Fame in Toronto and shown at the Bell Centre in Montreal or here in Edmonton at Rexall Place. Watch this film with your family it is a great movie. I also recommend the book in both French and English. Go Habs Go.

Prediction: Positive

>Exceptionally silly actioner with braindead leads in a story which would have suited a fill-in issue of Spiderman. The action sequences never really flow as they should, leaving some cool bits orphaned in a sea of sound and fury, signifying nothing. I really wonder how they'll release this one in the West. Sam Lee overacts like crazy, newcomer Edison Chan doesn't display any acting talent yet. The robot is clunky and not very impressive, and the CGI effects (though done by US sfx-people) are ridiculous, totally destroying any remaining suspension of disbelief. I am NOT looking forward to Gen-Z Cops...

Prediction: Negative
 
## Application
- Can be used by movie producers to get reviews in a statistical fashion without much cost.
- Can generate ratings on basis of positive and negative reviews

