This is the programming assignment 3 for Natural Language Processing class from Stanford University.

To implement a Naive Bayes classifer for text categories:
What need to do is to finish the 'addExample' and 'classify' functions in NaiveBayes.py

** Notes: 
   the data structure can be used as one's like.
   What I used is inserted in the '__init__' function.
   Two modules are imported: collections and math.
   'Defaultdict' is a useful tool to count the values in a dictionary.
   To run the classifer: "python NaiveBayes.py -f ../data/imdb1/"
   To do data preprocessing, I tried two ways:
   Firstly, to handle negations, resulting no effects on the accuracy.
   Secondly, to remove the nontations among the words.

** Results are as follows:
   [INFO]Performing 10-fold cross-validation on data set:../data/imdb1/
   [INFO]Fold 0 Accuracy: 0.755000
   [INFO]Fold 1 Accuracy: 0.815000
   [INFO]Fold 2 Accuracy: 0.845000
   [INFO]Fold 3 Accuracy: 0.815000
   [INFO]Fold 4 Accuracy: 0.810000
   [INFO]Fold 5 Accuracy: 0.825000
   [INFO]Fold 6 Accuracy: 0.815000
   [INFO]Fold 7 Accuracy: 0.815000
   [INFO]Fold 8 Accuracy: 0.745000
   [INFO]Fold 9 Accuracy: 0.825000
   [INFO]Accuracy: 0.806500

