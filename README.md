# Course-Project-2-IDM
Team09, Data mining course project-2
Malware Detection in Network Traffic Data

Problem Solved: - Performed binary classification on feature “label” containing Benign, Malicious using different classification models.
Before preprocessing: - 23 features, about 1 million entries
After preprocessing: - 19 features, 4 lakh entries
After Dimensionality Reduction: - 10 features,4 lakh entries  
 
Problems: - 1) Dataset was not in standard form
2) 10 different observations / 10 different datasets
3) Dataset containing too many ‘-’ values
4) Features having different data types
5) Categorical columns

Solution used: -
1) Used pandas inbuilt read csv's split functionality to convert the dataset in standard form.
2) Replaced the '-' values Nan values and removes the entries having nan values 
3) Manully converted all the features in numpy int64 data type.
4)Dimentionality Reduction:- Used Principle component analysis to reduce the feature dimention from 19 to 10 convering 96% of data.
5) Classification:- applied standard scaler to normalise the values, splitted the dataset into two parts test and train, trained and did classification on 5 classification models.
Selected classification models: - 
1)	Logistic regression
2)	K nearest neighbour
3)	SVM (hard margin and soft margin)
4)	Decision tree
5)	Random forest
Contribution: - 
Preprocessing was done by whole team. Then the classification model was evenly divided to the team members,
Pratham: - SVM hard margin, soft margin
Diti: - Random Forest
Prashuk: - Logistic regression
Swara: - Decision Tree
Digant: - K-nearest Neighbours. 
