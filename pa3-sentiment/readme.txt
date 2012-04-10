This is the programming assignment 3 for Natural Language Processing from Stanford University.

To implement a Naive Bayes classifer for text categories:
What need to do is to finish the 'addExample' and 'classify' functions in NaiveBayes.py

** Notes: 
   the data structure can be used as one's like.
   What I used is inserted in the '__init__' function.
   Two modules are imported: collections and math.
   'Defaultdict' is a useful tool to count the values in a dictionary.
   To run the classifer: "python NaiveBayes.py -f ../data/imdb1/"

** results are as follows:
   [INFO]Performing 10-fold cross-validation on data set:../data/imdb1/
   [INFO]Fold 0 Accuracy: 0.655000
   [INFO]Fold 1 Accuracy: 0.640000
   [INFO]Fold 2 Accuracy: 0.690000
   [INFO]Fold 3 Accuracy: 0.700000
   [INFO]Fold 4 Accuracy: 0.665000
   [INFO]Fold 5 Accuracy: 0.650000
   [INFO]Fold 6 Accuracy: 0.680000
   [INFO]Fold 7 Accuracy: 0.650000
   [INFO]Fold 8 Accuracy: 0.690000
   [INFO]Fold 9 Accuracy: 0.685000
   [INFO]Accuracy: 0.670500
