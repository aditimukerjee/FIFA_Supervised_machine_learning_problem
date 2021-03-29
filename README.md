# FIFA_Supervised_machine_learning_problem

Here I am exploring the FIFA set where I am predicting the what factors dectate whether a player is special and find a satisfactory model that will predict whether a player is special with a high r^2 value.

This is a big dataset with 90 attributes and 18k+ players.

Other point to remember is that I have not split the training and testing dataset in the beginning itself. In general splitting of data should be done in the beginning itself to avoid any data carryover.

The link to the dataset is as follows: https://www.kaggle.com/karangadiya/fifa19

The biggest challenges with this dataset are:

- Missing values
- Lots of data
- Many groups for categorical dataset
- Cleaning data with a mixture of values like €565K
- Performing upsampling

CONLUSION
Here XGBoost shows a r^2 value of 0.987. It is a good classifier to handle this non-linear data problem.

Overall, I really liekd working with such a huge dataset. I could have handled missing values better using knn and linear imputtaion for numerical data and better techniques for non-numerical.
