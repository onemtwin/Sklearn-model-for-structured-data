# Sklearn-model-for-structured-data
**About the Dataset**
##The dataset has:##
1. Columns  --5
2. column names--(initial, x2, add555, div5, minus11)
3. Rows--5000
4. Data type --
RangeIndex: 5000 entries, 0 to 4999
Data columns (total 5 columns):
 #   Column   Non-Null Count  Dtype  
---  ------   --------------  -----  
 0   initial  5000 non-null   int64  
 1   x2       5000 non-null   int64  
 2   add555   5000 non-null   int64  
 3   div5     5000 non-null   float64
 4   minus11  5000 non-null   float64
dtypes: float64(2), int64(3)
###for Column ;###
* **initial :** ==initial
* **x2 :** == (initial)*2
* **add555** == (x2)+555
* **div5** == (add555)/5
* **minus11** == (div5)-11

Conclusively, for small datasets with simple and predictable patterns, Scikit-Learn is preferable over tensorflow. [Reference](https://myscale.com/blog/scikit-learn-vs-tensorflow-choosing-right-tool-machine-learning/#:~:text=Scikit%2DLearn%20boasts%20a%20user,%2C%20images%2C%20and%20audio%20tensorflow.)
