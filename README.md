# The Challenge
This is the Amazon ML challenge 2023 where in we were suppsoed to predict the price of an item given the description of the item.
This entails us to first identify the item correctly and then predict the price of the item.
This is a seemingly easy task for a human but to train a machine for this process.

# Our Approach

### Path I
- We first took the description/keywords and tokenised it i.e., turned sentences to words
- Then we removed the words which are useless like prepositions and articles
- keeping only the meaningful words, we went on to join them to forma sentence
- this sentence was then summarised

### Path II
- Taking the description we summarised it using AI summarisers API.


# Process
Taking the "test_file.csv" run it through "dataCleaner.ipynb" to get cleaner data in a csv file, i.e., without NaN values and the text without stop words and lementised.
Make the so produced csv file go through "keywordSentenceCreator.ipynb" and generate another csv file.
Then this file should be passed through "predictor.ipynb" which generates the predicted product length values.
