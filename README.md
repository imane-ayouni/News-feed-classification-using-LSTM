# News-feed-classification-using-LSTM
A stacked LSTM to categorize textual news feeds

## Topic
In this notebook I will experiment with sequential data classification using LSTM. My dataset is comprised of news feed with their categories, the news feeds being a long paragraph of news
related to a special topic and topics being either sport, entertaimnent, tech, business or politics. I will need to do some pre-processing of the data including TF-IDF vectorization which 
maps each paragraph to a long vector comprised of the scores of the words within it. Then I will build an LSTM network that can classify the news to their correspondent category. So let's 
get started !

## Objectives
- Vectorize the news feeds to be machine learning ready
- Build an LSTM to categorize them

## Summary
- Importing libraries
- The dataset
- Label encoding the target
- Text pre-processing
- Train/Validation/Test splits
- Creating the dataloaders
- Building the network
- Training the network
- Testing the network
- Inference
- Conclusion

  ## Libraries
  - Pandas
  - Numpy
  - Torch
  - NLTK
  - Sklearn
  - Scipy

  ## Data source
  https://www.kaggle.com/datasets/ahmedashrafahmed/text-classification?fbclid=IwAR2oXktbbTlGmtm8-4XBx2T2zahPBIJSq3y-WuJPagkJgxpCchd47xDSLso
