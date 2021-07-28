# CNN-covid19-Xray-classification-webapp

train dataset link: https://drive.google.com/file/d/1jumurgtZWvpj60uJTTc2kKsJ9ii7FUT4/view?usp=sharing             
test dataset link: https://drive.google.com/file/d/1kjY-4mtdvzBwbn5-txZGIX5h86iTAU3Z/view?usp=sharing        

Classification of X Rays images as covid positive ,covid negative using ReLU basis activation function and adam optimizer in  web app
using MLPClassifier model from sklearn https://scikit-learn.org/stable/modules/generated/sklearn.neural_network.MLPClassifier.html, and using 
train_test_split model selection ,i was able to achive approximately 0.95 of accuracy.Process start with collecting data under same working directory and labeling of image as 0,1,2 for normal image,
positive image and 2 for image other than Xray image (error images), next loading of labeled data as features and targets.Then training dataset shuffeling for better accuracy,
train_test_split model slection and resahping the nparray between 0 and 1 based on pixels and featuers, target fitting into model. Then accuracy ,precision ,recal1 and f1 score calculation to evalute the output quality.
precision : defined as number of true positive over sum of true positive and false positive                                
recall: defined as numebr of true positive over sum of true positive and false negative

# web app design
Frontend : HTML,CSS                                     
Backend: Django                                        


homepage:
![hompage](https://user-images.githubusercontent.com/70704151/127347632-9139fa3e-d284-44f9-959d-fd70bb8a42a5.PNG)

working:

![pic](https://user-images.githubusercontent.com/70704151/127352413-a690cb9c-b03e-459a-b47e-f2d5dd8be5c0.PNG)

![res](https://user-images.githubusercontent.com/70704151/127352426-5036c8ee-3d3d-4b1c-a1a6-815518e34446.PNG)


# Note:
Result are predictions only not final diagnosis result
