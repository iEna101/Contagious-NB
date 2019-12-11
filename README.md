# Contagious-Naive-Bayes
With the increase in online social media interactions, the true identity of user profiles becomesincreasingly doubtful.
Fake profiles are used to engineer perceptions of opinions and also to cre-ate online relationships under false pretence.
Natural language text – how the user structures asentence and uses words – provides useful information to discover expected patterns,
given theassumed social profile of the user. We expect, for example, different word use and sentence struc-tures from teenagers than
from adults.  Sociolinguistics is the study of language in the context ofsocial factors such as age, culture and common interest. 
Natural language processing (NLP) pro-vides quantitative methods to discover sociolinguistic patterns in text data. Current NLP 
methods make use of a multinomial naive Bayes classifier to classify unseen documents into predefinedsociolinguistic classes. One
property of language that is not captured in binomial or multinomialmodels, is that of burstiness. Burstiness defines the
phenomenon that if a person uses a word, theyare more likely to use that word again.  Thus, the independence assumption between
respectivecounts of the same word is relaxed.  The Poisson distribution family captures this phenomenonand  in  the  field  of 
biostatistics,  it  is  often  referred  to  as  contagious  distributions  (because  thecounts between contagious diseases are
not independent).  In this research, we relax this countindependence assumption of the naive Bayes classifier by replacing the 
baseline multinomial like-lihood function with a Poisson likelihood function.  In the second stage of the NLP pipeline, weuse the
top words identified in each class to explore the conditional dependencies between thesewords. For this purpose, an unsupervised 
Bayesian network is trained on a bag-of-words vectori-sation of the top words.  The output of the second stage is an exploration
of the sociolinguisticpatterns among different groups of people. The proposed methodology is applied to two data sets.In both 
cases, the contagious naive Bayes classifier achieved the best results and we were able toextract word dependency structures from
the Bayesian network learning. The methods developedin this research has the potential to aid security institutions, forensic
investigations, and market re-searchers in identifying valuable sociolinguistic features associated with social groups of interest.
Key words: Sociolinguistics, Bayesian networks, naive Bayes classifier, contagious distributions.
