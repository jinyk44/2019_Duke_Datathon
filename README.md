# Customer Conversion Analysis based on Topic Interests
## Background
In digital advertising, “conversion” refers to the event  when the shopper clicks on the ad and performs a valuable action such as signup, registration, or make a purchase. Since “conversion” is a measurable event, it represents a reasonable proxy for the number of customers acquired during the ad campaign.  Increasingly, brands and agencies looking to put a value on the Return on Advertising Spend (ROAS), require marketers such as us to optimize the ad spend such that customer acquisition is maximized.
Since conversion events are extremely rare, being able to successfully identify the customers who are more likely to respond to ads and convert is crucial for the ad campaign.
## Objective
In this analysis, we try to identify the customers who are more likely to convert based on their interests in different topics. The dataset provided by Valassis is divided into two groups, training and validation. We first use training dataset to build our model to predict customers who are more likely to convert. Then using validation dataset to evaluate the performance of our model. Finally, based on the analysis of our model, we profiled the converted customers and made suggestions to Valassis on further ad campaigns. 
## Data Description
This dataset is provided by [Valassis](https://valassis.com/) and was used in the 2019 [Duke Datathon](https://dukeml.org/datathon/index.html). Valassis reserved all rights for the dataset.

 | File Name | Description |
 |---| --- |
 | training.csv | Training Data: Contains the samples needed to train the model Record count: 96,406 Positive samples: 1,465 Negative samples: 94,941 |
 | validation.csv | Validation Data: Contains the samples for validating the model. Record count: 80,008 Positive samples: 620 Negative samples: 793,88 |
 | interes_topics.csv | Contains the topic label and topic description. |


