# Decision Tree algorithms
Implementation of Decision tree algorithms

## Installation 
Run the following command to install:
```python
    pip install decisiontree
```

## Useage 
```python 
from ID3Algorithm import ID3
# object of the ID3 class can be created in 2 way
# 1. By passing both the train and test csv file
# 2. By passing a lists of data_train, data_test, features_train, features_test
id3_1 = ID3("PATH to TRAIN csv","PATH to TEST csv")
id3_1.build_tree()
id3_1.classify()

id3_2 = ID3(dataset_train,dataset_test,headers_train,headers_test)
id3_2.build_tree()
id3_2.classify()
```