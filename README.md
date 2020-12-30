# HLT
Twitter Sentiment Extraction

## Abstract
Classical sentiment analysis tasks aim to label a sentence as positive or negative. Our project will go one step further trying to identify which parts of the sentence (that in our case are tweets) contribute in labeling it as neutral, positive or negative. 
To perform this job, we used a model composed of three layers. 
The first layer is a BERT transformer while the third layer is a Neural Network. 
The second layer has been tested with three possibilities: GRU, CNN and GRU + CNN. We will compare the models pointing out the best one, and trying to understand why it obtained the best values.

The code can be found in the code folder
