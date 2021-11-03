## BITCOIN ADDRESS DETICITION 

Since the goal of this project is to predict if that address has been used to receive ransoms in the past, So the target is the label column which represent two classes (white, ransomewhere ) . 
- The positive class is the "White label" will takes '0' as value.              
- The negative class is any kind of "ransomware label" will takes '1' as value.

The figure below shows the confusion matrix with logistic regression classifier.
![confusion_matrix](https://user-images.githubusercontent.com/36573740/140067750-e29ce99d-24d8-4402-9a38-632a1e902c2f.jpg)
The classifier failed to distinguish between the two classes due to the imbalanced classes issue, the next step is to handle this issue and bullied the model again.
