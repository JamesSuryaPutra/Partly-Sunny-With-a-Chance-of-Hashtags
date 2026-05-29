# Partly Sunny With a Chance of Hashtags
<img width="640" height="122" alt="image" src="https://github.com/user-attachments/assets/570aa1d9-ded5-48fc-a14b-c6cca1002b3c" />

# Description
In this competition you are provided a set of tweets related to the weather. The challenge is to analyze the tweet and determine whether it has a positive, negative, or neutral sentiment, whether the weather occurred in the past, present, or future, and what sort of weather the tweet references. It's a lot to mine from so few characters, but if the going gets tough you can always blame the weather...

"Please knock out the power giant storm that is passing thru....please." -Tweet #74096

# CrowdFlower
We are excited to team up with CrowdFlower on the first of what we hope will be many fun machine learning projects. CrowdFlower is debuting a new open data library and we're always looking for an excuse to have a competition. Why is this exciting? Sweet, sweet Labels.

Data repositories sometimes have more in common with a landfill than a library. They're home to tattered piles of spreadsheets in odd formats with nary a shred of documentation to tell the GDP of Chile from the migratory patterns of North American goldfinches. If creating value from this digital exhaust is a defining theme of the big data explosion, most repositories leave you choking on the diesel fumes of data disappointment. Such data is great if you are doing a report on the GDP of Chile, but not so useful if you are doing machine learning, or its red-headed step child, data science.

Crowdflower's data sets provide the thing that makes so many repositories fall short - data paired with labels. One can decide whether two English sentences are related, make judgments about yogurt chatter, or rank emotions on tweets about nuclear energy. It's all about the (wo)manpower to label what these bytes actually mean.

# The Open Data Library
CrowdFlower Open Data Library is a repository of real data set samples that developers, researchers and data scientists can download and use to test and improve algorithms. Our mission is to encourage users to explore the possibilities and power of crowdsourcing. Open Data is free, available to anyone, and ready-to-use with CrowdFlower’s Platform.

New data sets are continuously added to CrowdFlower Open Data Library as users of the CrowdFlower Platform opt-in to share their data with the crowdsourcing community. Sample data sets currently available include tweets for sentiment and topic analysis, word combinations to test similarities, sentence combinations to test related topics, and more. Learn more at www.crowdflower.com.

# Prizes
The winning team will be rewarded $500 of credit on the Crowdflower platform. It is strongly encouraged (bordering on peer pressure) that this is used to create a dataset for the next Crowdflower research competition on Kaggle.  We hope that this initiative can generate great problems and new datasets for everyone to enjoy.

If the winning team is not interested in creating/labeling a dataset, we will continue to offer the prize to the highest team that is interested.

# Evaluation
The Root Mean Squared Error ("RMSE") is used to measure the accuracy:
<img width="189" height="68" alt="rmse" src="https://github.com/user-attachments/assets/5a3b6fea-d6e9-4546-86a6-8599b441d571" />

Where:
- \\( n \\) is 24 times the total number of tweets.
- \\( p_i \\) is the predicted confidence rating for a given label.
- \\( a_i \\) is the actual confidence rating for a given label.

# Submission Format
For each tweet in the test set, predict the confidence score for each of the 24 possible labels.  Submission files should be in the following format and must have a header.
<img width="446" height="86" alt="submission" src="https://github.com/user-attachments/assets/2983955f-e9e6-43be-abb1-b4fb5a16e5d9" />
