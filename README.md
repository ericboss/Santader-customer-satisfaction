# Santader-customer-satisfaction

## Project Motivation

The aim of this project is  to predict if a customer is satisfied or dissatisfied with their banking experience

## File Description

- [Santander_Customer_Satisfaction](https://github.com/ericboss/Santader-customer-satisfaction/blob/master/Santander_Customer_Satisfaction.ipynb): A Descriptive Jupyter Notebook

### Install

This project requires **Python 3** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [lightgbm](https://lightgbm.readthedocs.io/en/latest/)
- [eli5](https://eli5.readthedocs.io/en/latest/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

I recommend you install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project. 

## Results of the project

Results and discussion were published on Medium: [Machine learning can predict whether a customer is happy or not](https://medium.com/@ericnguifo/machine-learning-can-predict-whether-a-customer-is-happy-or-not-7037f8761b6d)
The results can be summarized as follows:
- The project is about predicting whether the customers of a business will be happy or not with the business’s product.To illustrate that, we used the dataset Santader released on kaggle.
- Some data visualizations was done and showed for example that unhappy customers used less products.
- Some data processing was done and clustering was also implemented to group data with similar features.
- Machine learning was then used to predict customer’s satisfaction where an auc of 0.841805 was obtained.
The top 20 features relevant to prediction was then displayed.

![alt text](https://github.com/ericboss/Santader-customer-satisfaction/blob/master/Screenshot%20(760).png)

