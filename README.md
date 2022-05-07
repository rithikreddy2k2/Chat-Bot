# Chat-Bot
## We'll be Using Babi Data set from Facebook Reasearch
## We Unpickle the data and then Vectorize the data.
## Then we Tokenize the vectors(i.e., integer encoding the Sequence of Words)
## Then we Functionalize Vectorization as Follows:
### Vectorizes the stories,questions, and answers into padded sequences. 
### We first loop for every story, query , and answer in the data. Then we convert the raw words to an word index value. 
### Then we append each set to their appropriate output list. Then once we have converted the words to numbers, we pad the sequences so they are all of equal length.
## Then, we Build the Network by adding Models and Layers over it and finally save the Model for Future use
## Finally, we Evaluate the Model firstly on the Test set and we Get 99% accuracy
## LAter we Write our Own stories and Questions and Yet we get pretty good results with accuracy of around 95% 
