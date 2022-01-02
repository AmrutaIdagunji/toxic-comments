# toxic-comments

The dataset is available in Kaggle - https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/overview

A toxic comment can be anything that's rude, insulting, threatening or disrespectful. Toxic comments can be more specifically grouped or pointed towards a particular race (asian, hispanic, latino etc), gender (male, female, bisexual, trans etc.) and sexual orientation (gay, lesbian, transgender etc.).

The ipynb file imports the test set from google drive. Since the training data is huge, saving it in drive and accessing it in jupyter notebook wasnt successful. NOTE: To run the file, make sure to download the dataset and provide the correct path in the cell.

Here, bag-of-words model is used to convert the text/comments into a vector and then a Decision Tree regressor is run to determine the toxicity of the comment.

Mean Squared error of 0.39 was obsvered. 
