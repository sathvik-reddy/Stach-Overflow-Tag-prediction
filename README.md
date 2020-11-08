# Stach-Overflow-Tag-prediction
Problem Statemtent
Suggest the tags based on the content that was there in the question posted on Stackoverflow.

Approach:

Data analysis is done to know the avg number of tags per question,total number of unique tags and to know number of times each tag appeared

And then out of all tags we are filtering out most used 500 tags with which we can represent about 90% of the questions

As we are taking 500 tags we need to train 500 classifiers and of all the classifiers Logistic Regresion is proved to perform very well

