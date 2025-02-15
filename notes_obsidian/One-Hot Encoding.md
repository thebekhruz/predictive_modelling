**One Hot Encoding is a _**method for converting categorical variables into a binary format.**_ It creates new columns for each category where **1** means the category is present and ****0**** means it is not. The primary purpose of One Hot Encoding is to ensure that categorical data can be effectively used in machine learning models [link](https://www.geeksforgeeks.org/ml-one-hot-encoding/)

1. **Eliminating Ordinality**: Many categorical variables have no inherent order (e.g., “Male” and “Female”). If we were to assign numerical values (e.g., Male = 0, Female = 1) the model might mistakenly interpret this as a ranking and lead to biased predictions. One Hot Encoding eliminates this risk by treating each category independently.
2. **Improving Model Performance**: By providing a more detailed representation of categorical variables. One Hot Encoding can help to improve the performance of machine learning models. It allows models to capture complex relationships within the data that might be missed if categorical variables were treated as single entities.
3. **Compatibility with Algorithms**: Many machine learning algorithms particularly based on linear regression and gradient descent which require numerical input. It ensures that categorical variables are converted into a suitable format.


