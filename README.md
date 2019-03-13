
# nobbas_assignment

Solution to the Machine Learning Assignment for Internship at Nobbas Technologies

## My Approach

* I used Pandas module for data handling and cleaning since it comes with a large number of builtin functions.
* I loaded the provided datasets and observed the various features and values after which I found out that the `CSV 2` and `CSV 3` files were useless since they contained features with only `0` values.
* After that, I removed the various features which either contained lots of null values or were not very useful for making prediction.
* Then I converted various categorical features from text to numerical form.
* Then I trained various classification algorithms on the data and evaluated their performance.

## Observations

* Simple classification models such as Logisitic Regression and KNN fail to gain high accuracy.
* Ensemble models such as Random Forest and Ada Boost Classifier gives good accuracy, but as the size of dataset grows the training will become slower and also the performance will degrade.
* Classification using Neural Networks would be the best way, regardless of the type of data provided, because it would be able to take advantage of all the different features and also there are lots of hyperparameters to play with so they can be fine tuned to perform even better.

### References

I referred to the official documentation of the modules to understand the usage of functions
**Pandas :** [https://pandas.pydata.org/pandas-docs/stable](https://pandas.pydata.org/pandas-docs/stable)
**Scikit Learn :** [https://scikit-learn.org/stable](https://scikit-learn.org/stable/)
**Matplotlib :** [https://matplotlib.org/3.0.3/index.html](https://matplotlib.org/3.0.3/index.html)
