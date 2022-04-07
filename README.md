# Python - DataPreprocessPractice
In this notebook, I am practicing simple, basic data preprocessing and visualizing things with some Machine Learning and Deep Learning in order to keep my knowledge fresh about everything. 

Various techonoliges have been used in order to make data handling efficient.

## Technologies

In this Notebook, i have used TensorFLow/Keras, PyTorch, Scikit-Learn, matplotlib and  other technologies. 

## Dataset
The data can be found in the dataset folder, which consists the training and the test set. Both files are a .csv files.

## The Task
The task was to predict a house's price based on many housing features. A total of 81 features were present in the data. Howewer, this is a simple linear regression task, so i tried to focus more on the data engineering part of the problem, trying out various data preprocessing technics.

### The architecture of the notebook
The very top section contains the imports and the data loading parts. The mid section has all the preprocessing methods like:
- Handling missing values
- Imputing values
- Binning and discretization
- Creating correlation matrix
- Searching for relationship betwen features based on the corr. matrix and subplots
- Data encoding
- Predicting missing values with normal equation and a simple linear model
- Outlier detection
- etc.

### Models
Since this is just a basic regression task, model building and hyperparameter tuning was not in the focus. First I made a simple Linear model with scikit-learn, then an NN model with keras. Furthermore, I have used feature selection models like the ExtraTreeClassifier or the Chi sqr method.
## Results
With the Linear model, i got an accuracy of ~85%, and with the feature subset selection models a little bit of less. 
With the the NN model, i have succesfully got the loss down to around 0.1% without overfitting.
