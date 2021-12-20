# Personality-Spectrum-Analysis

**Objective:** <br />
Myers Briggs test is one of the most popular personality tests used in the world.
We will be using the dataset extracted from Myers Brigg’s to train our model with the motive of predicting the personality type of a person after taking one sentence as an input.
MBTI (Myers Briggs Type Indicator) is primarily divided into 4 axes on the following scale:-
• Introversion – Extroversion (I-E)
• Intuition (N) – Sensing (S)
• Thinking (T) – Feeling(F)
• Judging (J) – Perceiving (P)
Objective from the model is to predict the personality type of a user after they input one sentence expressing some random thoughts in their mind. There are different labels of personality which is preferred by that person and using different modelling techniques we can describe person’s preference and behavior.

**Data:** <br />
 Source – Kaggle ( https://www.kaggle.com/datasnaek/mbti-type )
The dataset contains over 8600 rows of data, on each row is a person’s:
 • Type (This persons 4 letter MBTI code/type)
• A section of each of the last 50 things they have posted (Each entry separated by "|||" (3 pipe characters))

**Conclusion:** <br />
Different machine learning models were used for personality type prediction based on MBTI personality type indicator. The XG Boost model, which is an optimized distributed Gradient Boosting library in Python for implementing machine learning algorithms performed best among other models which were used. The accuracy of the XG Boost model was calculated and its performance were compared with other models which were used for the dataset. Along with this, other python libraries were also used such as Pandas, NumPy, Plotly, NLTK Seaborn, Matplotlib and Sklearn. We get good accuracy in predicting the different personality categories - Introversion (I)–Extroversion (E), Intuition (N)–Sensing (S) , Feeling (F)– Thinking (T) and descent in Judging (J)–Perceiving (P) personality category. This can be used by different NLP practitioner and psychologists in identifying different personality types and associated cognitive processes.
Application of machine learning in psychological research is increasing drastically over and there can be lot of areas in which it can be implemented such as recruitment system, criminal investigation, personal counselling system, online marketing etc. Having profound knowledge in Artificial intelligence and ML (roots of which can be traced back to the functioning of a human brain like Perceptron) will help in in the field of psychological research allowing us to broaden our perspective of individuals and understand the human mind more.
 
