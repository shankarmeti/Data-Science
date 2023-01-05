IDE : Jupyter Notebook

Library Used : NumPy, Pandas, Sklearn and stats

Data collection: With help of Kaggle website i have downloaded the all the datasets.

Data Understanding: By importing the dataset with the help of PANDAS library in the jupyer notebook. Understanding the dataset by checking the shape of the dataset, data types of each variables, information of dataset and checking the duplicates in the dataset.


Data cleaning:Handling the missing values in the dataset.

Categorical variables : Filled the missing values with mode

Numarical variables :numarical variable with more skewed then i have used medain to fill the missing values andfor numarical variables with less skewed variables i have used mean to fill the missing values.

Handling the ouliers in the numarical variables : I have used multiple transforamtion techniques to handle the outliers in the numarical variables
for example : Log transforamtion techniques and Power transforamtion techniques ( Geo johnsons and BOXCOX ).

Feature Engineering : I converted some variables from numarical to categorical and categorical to numarical variables based on the observation.

Handling the categorical variables : I have used multiple encoding techniques for the categorical variables.
Categorcal variables with 2 unique categories : One Hot encoding (Dummy encoding method)
Categorcal variables more then 2 and less then 10 unique categories : Label encoding method
Categorcal variables more then 10 unique categories : Frequence encoding method.

Feature scaling : I have used standerd scalar and min max scalar to bring the all numarical variables into same range.

Train Test split : With the help of sklearn library i have splited the dataset into two parts ( 70% train data, 30% test data ) to bulid machine learing models.
