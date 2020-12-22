# App Update NLP Classification
The Dataset that we have used consist of each update logs for every mobile application that were being posted on Playstore by the developers. The total dataset size is 7GB consisting of 8,66,138 update logs of both Android as well as iOS mobile applications.

# Goals
Topic Based classification of App Update logs to sort each update into a categories of update that it falls under.

# Pre-processing
Out of the 276 column features, using the "Description" feature that contains each app update information provided by the developers that will help in building a classifier. Using sentence level classification as each update log consist of multiple sentences.

# Models
We have used various models to record the best coherence score to determine the best suited model for our dataset namely BERT, LDA, and BERT-LDA. Based on the coherence scores, we were able to validate the BERT-LDA model fits right for our inputs. 

# Outputs
The output CSV file consist of the model output sentence level classification created by the BERT-LDA that will be appended to the original dataset for better understanding.
