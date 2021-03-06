# Analysis of a public online retail data set.

* data set available from: https://archive.ics.uci.edu/ml/datasets/Online+Retail

---

The Jupyter notebook stored in this repository is the output of a couple of days of exploratory
data analysis of an online retail data set. The code isn't elegant, beautiful, or optimized, it's just what I
hacked together in a short time for my own interest.

The purpose of this work was to see what value could be extracted from a fairly large and open-ended dataset (as opposed to one of the more straight forward Kaggle
data sets with a more obvious target vector, for example).

The analysis includes some basic feature engineering and machine learning. I also used the
opportunity to test Microsoft's LightGBM algorithm - I didn't have access to high performance
computing resource and the algorithm served me well in terms of speed and accuracy, compared with
XGBoost).

**Note:** There are a few plots made using Plotly which don't render in the repository view of
the notebook. You will have to clone and run it locally to see them. I'll see if I get time to
build Altair versions.

## ToDo:

 * complete the NLP section to build categories for the free text description of items.
 * build some better features and make some better predictions!

 ---

