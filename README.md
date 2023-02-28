# Spoiler-detection-in-unsolicited-movie-review-in-tweets

# Abstract

The approach for spotting spoilers in uninvited movie reviews on Twitter is suggested in this study. The suggested method is text classification it finds potential spoilers in a tweet Using BERT. The procedure entails gathering a labelled dataset containing spoilers and non-spoilers, pre-processing the data, adjusting a pre-trained BERT model on the dataset, assessing its performance, and deploying it for automatic spoiler detection in production. We can create a successful spoiler detection system by using BERT's capacity to learn crucial aspects for categorization.

# Required Libraries

snscrape\
pandas\
emoji\
re\
string\
nltk\
transformers\
tensorflow\
numpy\
torch

To install all the necessary libraries required to run this project, Run the following command.

```pip install -r requirements.txt```

# Dataset

Dataset is tweets collected about 4 movies (Divergent, The Bookthief, Sourcecode and Hugo). 1000 tweets per movie is collected and those 4000 tweets are labelled manually. 

# Model

BERT model is used to train the dataset
