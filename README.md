# MTIB_NLP PYSPARK
A NLP model to predict personalities

### The Myers Briggs Type Indicator (or MBTI for short) is a personality type system that divides everyone into 16 distinct personality types across 4 axis:

Introversion (I) – Extroversion (E)
Intuition (N) – Sensing (S)
Thinking (T) – Feeling (F)
Judging (J) – Perceiving (P)

So for example, someone who prefers introversion, intuition, thinking and perceiving would be labelled an INTP in the MBTI system, and there are lots of personality based components that would model or describe this person’s preferences or behaviour based on the label.

It is one of, if not the, the most popular personality test in the world. It is used in businesses, online, for fun, for research and lots more. A simple google search reveals all of the different ways the test has been used over time. It’s safe to say that this test is still very relevant in the world in terms of its use.


With that data we want to make an NLP model to predict based on comments (on social media) what is the kind personality a person has.

### Important:
#### The data is unbalanced and it has many personalities. Which is a problem hard to solve.

### First we start with a Base Line model. We clean the data, explored the data nad trained the model. 
The result was fair for a base line, but it had a very poor predictive power.


### The second model we only use 40 plus posts. the mdoel imrpoved little to nothing

### In the thrid model, we dumped types with too much data. Which improved the model to .4 f1 score

### In the forurth model, we dumped types with too little data. Which improved the model to .44 f1 score
 Notice that it would be two different models. One for the personalities taken in the third model and other to the personalities taken in the fourth
 
### Finally we solve the data unbalanced problem by reducing all types to only 280, 180 and then to 120. The results were similar and not significant.


URL KAGGLE DShttps://www.kaggle.com/datasets/datasnaek/mbti-typURL KAGGLE DS    
