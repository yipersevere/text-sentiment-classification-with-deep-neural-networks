## SVM

## VADER 



check the consistent size of reviews and sentiment :  review size :  8977 sentiment size:  8977
 X train shape for train data :  (7181,)=================================================================================VADER elapsed time:  2.45  s
test size length:  1796
VADER metrics report:
             precision    recall  f1-score   support
          0       0.78      0.42      0.54       174          1       0.94      0.99      0.96      1622

avg / total       0.92      0.93      0.92      1796

VADER confusion matrix:
[[  73  101]
 [  21 1601]]
0 params - {'vect__ngram_range': (1, 1)}; mean - 0.97; std - 0.00
1 params - {'vect__ngram_range': (1, 2)}; mean - 0.97; std - 0.00
SVM elapsed time :  7.37  s
SVM metrics report:
             precision    recall  f1-score   support

          0       0.92      0.75      0.83       174
          1       0.97      0.99      0.98      1622

avg / total       0.97      0.97      0.97      1796

SVM confusion matrix:
[[ 131   43]
 [  12 1610]]