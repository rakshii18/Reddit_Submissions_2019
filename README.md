# Reddit_Submissions_2019
I have created and thoroughly compared 3 different classification models for the reddit submissions data. 
Note:
Train/Test/Validation split: I have used the data corresponding to the year 2019 (the first 8 months only). 
The first 4 months are used for training, the next 2 months for test and the next 2 months for validation.

Size: The dataset is very big, so I have extracted 10,000 rows from every month and used it for modelling.

Class Label: the class label is given in the field named “score”. This looks like a regression problem.
However, I converted the problem into a classification one. For example, after plotting the class label histogram,I came up with ideas 
about how to convert the score to a categorical variable like {“popular”,”not-popular”}. I played around with different values to set the
threshold, only to realise that the value of threshold could determine if the dataset was imbalanced or not.

It is very important to perform feature engineering to obtain better values. This data set proved to be a very good learning point for me as it
was very challenging to overcome some of the hiccups.
Unfortunately, as I don't have much knowlegde about Natural Language Processing I could not work much on the non-numeric data. I believe that
this non-numeric data is a gold mine of information.

Link to accessing the data: https://files.pushshift.io/reddit/submissions/

