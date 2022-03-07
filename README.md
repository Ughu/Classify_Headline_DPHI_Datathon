# Classify_Headline_DPHI_Datathon
Jupyter notebook on a challenge part of NLP Bootcamp at DPHI.

The data necessary is uploaded here.

It is a bit ram consuming so Id advise running on Kaggle.

The biggest challenge is data processing. NLP is very data processing intensive as it is in this stage that you´ll turn your data into a way the selected algorith
will "understand" text and context.

In this notebook i went for Count Vectorizer wich came up with a sparse matrix with 23k features.
The problem I see here is that each headline has few words so we´ll end up with lots of zeros.
I would like to find a way to do this classification using context or relation between words to see if we could improve.

As it is I got a avg acurracy of 87%.
Precision of 88% for "is_sarcastic".
Recall score got 82% for "is_sarcastic".
True positive rate (from all the really sarcastic headlines the percentage of what the model classified as sarcastic) of 74%.

