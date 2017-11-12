<h1>Coursera: Practical Maschine Learning Assignement    </h1>

First I download the data and remove the blanks and NA values
<p></p>
<b>#read data
<b>a=read.csv('pml-training.csv',na.strings=c('','NA'))
 <p></p>
b=a[,!apply(a,2,function(x) any(is.na(x)) )]
 <p></p>
c=b[,-c(1:7)]</b></b>
 <p></p>
[1] 11776    53
[1] 7846   53
We have 19622 observations with 53 predictors
 <p></p>
The next phase is installing and loading of needed librarys
 <p></p>
<b> #needed packages
<p></p>
install.packages('randomForest')
<p></p>
library('randomForest')
<p></p>
install.packages('caret')
<p></p>
library('caret')
<p></p>
install.packages('e1071')
 <p></p>
library('e1071')</b>
<p></p>
Next we split our data into two subgroups 60:40 for cross validation
<p></p>
<b>#Building subgroups
 <p></p>
subGrps=createDataPartition(y=c$classe, p=0.6, list=FALSE)
subTraining=c[subGrps,]
 <p></p>
subTesting=c[-subGrps, ]
 <p></p>
dim(subTraining);dim(subTesting)</b>
<p></p>
[1] 11776    53
[1] 7846   53
<p></p>
We have 11776 observations in the Training- and 7846 observations in the Testing-Group
<p></p>
For the prediction task I decided to take the random forest algorithm. The modell will be trained
on the Training Group,the predicted Outcome will be taken from the testing group. With this data, the confusion matrix shows
the performance of the algorithm
<p></p>
<b>model=randomForest(classe~., data=subTraining, method='class')
 <p></p>
pred=predict(model,subTesting, type='class')
 <p></p>
z=confusionMatrix(pred,subTesting$classe)
 <p></p>
save(z,file='test.RData')
 <p></p>
load('test.RData')
 <p></p>
z$table</b>
<p></p>
          Reference
Prediction    A    B    C    D    E
<p></p>
         A 2229    9    0    0    0
<p></p>
         B    3 1507    3    0    0
<p></p>
         C    0    2 1363   18    5
<p></p>
         D    0    0    2 1267    9
<p></p>
         E    0    0    0    1 1428


<p></p>
 The accuracy of the model is z$overall[1]
<p></p>
<b>z$overall[1]   </b>
 Accuracy
0.9933724
<p></p>
The last step is reading the training data and train the modell on this data.
<p></p>
<b>#reading testing data
d=read.csv('pml-testing.csv',na.strings=c('','NA'))
 <p></p>
e=d[,!apply(d,2,function(x) any(is.na(x)) )]
 <p></p>
f=e[,-c(1:7)]

#predictions
predicted=predict(model,f,type='class')
 <p></p>
save(predicted,file='predicted.RData')
     <p></p>
load('predicted.RData')
 <p></p>
predicted
</b>
<p></p>
Here are the predictions for the 20 Values
<p></p>
 1  2  3  4  5  6  7  8  9 10 11 12 13 14 15 16 17 18 19 20
 B  A  B  A  A  E  D  B  A  A  B  C  B  A  E  E  A  B  B  B
Levels: A B C D E
<p></p>