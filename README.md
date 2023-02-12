# **Project description**

Nowadays banks all over the world use direct marketing campaigns in order to gain new clients who will subscribe term deposits. They all face the same problem of choosing the right people who will become potential clients.  If the people who are phoned are chosen randomly there is a high probability that the person will not be interested in the offer and it will be a waste of time for the employee. On the other hand, people who can be potentially interested in subscribing term deposit may not even be phoned. Thanks to the predictive models there is a possibility to increase the knowledge whether the person will subscribe or not a term deposit which will result in the optimization of time of work of employees of the banking institution and will result in increase of benefits for the company. In this project 3 different models will be built and compared: classification tree, random forest and neural network. Hyperparameters for each model will be tuned in order to increase their predictive power. From the business point of view it is important to increase the true positive rate and accuracy of the model. It is very important to detect clients who will subscribe a term deposit, because it gives capital for bank that can be used for giving loans and credits. But, it is also very important to know that a certain client will not subscribe a term deposit. It can save a lot of time spent on preparing direct marketing campaign for this person. Thus, it is also essential that model can accurately predict both positive and negative values. Due to this reasons for each of 3 types of models 2 distinct models will be built. First one with objective to increase accuracy and second one with objective to increase sensitivity. Then the results of different types of models will be compared.

# **Data**

Data file used in this project can be found under this link:
https://archive.ics.uci.edu/ml/datasets/bank+marketing

# **Technologies used**

Project was made in R Markdown using below libraries:

* plyr
* gridExtra
* ggplot2
* corrplot
* cluster
* factoextra
* caret
* rpart
* randomForest
* nnet
* ROCR

