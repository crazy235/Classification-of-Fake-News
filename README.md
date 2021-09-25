<h1 align = "center"> Fake News Classification </h1>

In this modern era, Connection between the people is grown to such an extent that was newer before in the history. Along with this information between people is shared in fraction of seconds. With the help of this some people take advantage and try to spread fake news. So, It's important to know the information shared was right or wrong before beliving in it.

<h2 align = "center">Pre requsites</h2>

- Knowledge on Python
- Knowledge on Databases
  - Database can be in different formats. Some examples of Databases as follows:
    1. Excel format
    2. CSV format
    3. SQL Database
- Knowledge on Python Frameworks:
  1. Numpy
  2. Pandas
  3. XG Boost
  4. Scikit Learn

<h2 align = "center">Computational Environment</h2>

You can use any one of the environments mentioned below to run this code. I have used Jupyter Notebook extesnion in vs code.

- Jupyter Notebook
- Google colab

You can also prepare it python file.

<h2 align = "center">Installing Libraries</h2>

Installing Pandas

> pip3 install pandas

Installing NumPy

> pip3 install numpy

Installing XGBoost

> pip3 install xgboost

Installing Scikit

> pip3 install -U scikit-learn

> or

> pip install -U scikit-learn

<h2 align="center">Database or Dataset</h2>
The Data Set is included in this repository as a CSV file.

<h2 align = "center">Importing Dataset</h2>

- You can diretly paste our link which is a CSV file while reading the file into the program.

```python
      read_csv("link")
```

- You can copy the data in a file and save it in CSV format.

```python
      read_csv("filename.csv")
```

- You can make a table in SQL and insert all these values. To read such SQL table we have a command as follows.

```python
      read_sql(connection to database)
```

<h2 align="center">Passive Aggressive Classifier</h2>

- Passive: If the prediction is correct, keep the model and do not make any changes. i.e., the data in the example is not enough to cause any changes in the model.
- Aggressive: If the prediction is incorrect, make changes to the model. i.e., some change to the model may correct it.
- Classifier: A classifier is a type of machine learning algorithm used to assign a class label to a data input.

1. If you want to work on big data, this is a very important classifier.
2. Using this classifier we can handle data from a social media website like Twitter as input.
3. There will be a huge amount of data coming in every second and this classifier will be able to handle data of this size.
