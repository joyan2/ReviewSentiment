# Indicate the name of the program
# Give a short description of the problem solved
# Give a short description on how to run your code

Movie and Yelp Review Sentiment Analyzer

This program takes in reviews that are marked "Positive" or "Negative", and trains models to predict which category a review belongs in given its text.

term-project provides the baseline system for the Movie Review dataset and can be run as it is.
term-project_improved provides attempts at improving the baseline system. There are four modifications marked by comments, and each one can be commented out to provide a different mix of features. If TfidfVectorizer() is used, then the line above it, CountVectorizer(), should be commented out.

Similarly, EC_base provides the baseline system for the Yelp Restaurant Review dataset, while EC_improved provides the improved system. The code is similar and the same areas can be commented out.