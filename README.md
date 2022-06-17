# Predicting Mental Health using Machine Learning

## Description
This project implements a [research paper](./resources/Predicting_Individuals_Mental_Health_Status_in_Kenya_using_Machine_Learning_Methods.pdf) which aims to find a classifier model to predict Mental Health status of individuals. The paper is selected after reviewing various papers on the topic of mental health. The project is done as a course project for the 'BITS F464 Machine Learning' course instructed by Dr. Paresh Saxena.<br>
More details of the project can be found in the [report](./resources/report.pdf) and [demo presentation](./resources/demo-presentation.pdf).

## Dataset and Pre-processing
### Dataset description
The dataset is based on a survey conducted by Busara Center in Western Kenya. It contains information pertaining to individuals' health, financial conditions among other things.<br>
The [dataset folder](./dataset/) contains training data, testing data and the descriptions of each feature of the dataset.

### Pre-processing
- Filling NaN values with the mode of given data
- Feature selection using Random forest importance technique

## Models
The models used are classifiers- SVM, Logistic Regression, Decision Tree, Random Forest, Gradient Boosting and Vote Ensembling of these models. These models are used while tuning various hyper-parameters where necessary. <br>
Finally, the conclusion is that the classifiers- Vote Ensembling, Random Forest and SVM with radial basis kernel yield the best F1 score and accuracy.

## The Team
- [Shashivardhan Vadyala](https://github.com/ShashiWerdun)
- [Chaitanya Chakka](https://github.com/ChiatanyaChakka)
- [K S V L Druthi](https://github.com/KSVLDruthi)
- [Sheethal Reddy](https://github.com/Chotu2023)
- Pranay Kumar Dasoju
- Vansh Madan