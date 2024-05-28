# Categorizing-google-play-store-app-reviews

In the modern world, customers rely heavily on internet reviews while making decisions. With the growth of e-commerce, online stores, and mobile applications, consumers now primarily rely on reviews to guide their purchases. Because of this, companies are becoming more and more interested in examining user reviews to learn more about the preferences and levels of customer satisfaction.
Opinion mining, or sentiment analysis, is a common operation carried out by data scientists to automatically classify user reviews as neutral, negative, or favorable. Thanks to the abundance of data accessible, sentiment analysis has grown in importance as a tool for organizations looking to understand the preferences and behavior of their customers.
The goal of this project is to use the Python Scikit-learn module and a Naive Bayes classifier to create a sentiment analysis classifier. 

# Modeling
The Naive Bayes method is employed due to its simplicity, speed, and suitability for handling substantial amounts of data. This probabilistic approach performs well in text categorization applications including recommender systems, sentiment analysis, and spam filtering.
The Naïve Bayes algorithm comes in three varieties. Below is a list of the three types: -
__Gaussian naive Bayes__
__Multinomial naive Bayes__
__Bernoulli Naïve Bayes__
Multinomial Naive Bayes was shown to be the most appropriate and well-suited model for text classification tasks, especially when handling discrete data like word counts. Given that the reviews on the Google Play store are text-based, with each review being composed of discrete words, the Multinomial Naive Bayes algorithm is a suitable option for this purpose.
