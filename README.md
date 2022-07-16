# Sonar - Mines and Rock classification #

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jofaval/sonar/blob/master/notebook.ipynb)

## Table of contents

1. [📁 Data](#-data)
1. [📓 Description](#-description)
1. [✔️ Objective](#-objective)
1. [🧱 Tech stack](#-tech-stack)
1. [💹 Algorithms](#-algorithms)
1. [📊 Visualization](#-visualization)
1. [🤓 Conclusions](#-conclusions)
1. [©️ Credits](#-credits)

## 📁 Data
[↑ Back to the table](#table-of-contents)

The data is available at the official archive link:\
[https://archive.ics.uci.edu/ml/datasets/connectionist+bench+(sonar,+mines+vs.+rocks)](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+(sonar,+mines+vs.+rocks))

## 📓 Description
[↑ Back to the table](#table-of-contents)

**Abstract**: The task is to train a network to discriminate between sonar signals bounced off a metal cylinder and those bounced off a roughly cylindrical rock.

It's a set of signals from 0 to 1 that represent the information about an object. This dataset is a famous dataset for (binary) classification.

## ✔️ Objective
[↑ Back to the table](#table-of-contents)

To succcessfully predict wether it's a rock or a mine, it is said that, a classification model with a score above 80% is considered a good model. A simpe (not to say easy) objective makes it easier to focus on the project.

## 🧱 Tech stack
[↑ Back to the table](#table-of-contents)

Python, that's it! R is a programming language that, as for the moment being, I have no experience with, even though it's powerful and broadly used, but I'd dare to say that no more than Python.

And one of the strongest points, if not the most, about Python, are it's libraries, so... the libraries I've used are:

- Pandas, data manipulation with an ease of use and exploration data analysis.
- Numpy, a really strong linear algebra library, used in the project for it's statistics utilities, SciPy may be an alternative, but I have no experience at all with it.
- Matplotlib and Seaborn, both fantastic libraries for data visualization, and they complement each other.
- Scikit-Learn, the library used for Machine Learning and statistics models: Linear Regression, SVR, Lasso, Ridge, etc.

## 💹 Algorithms
[↑ Back to the table](#table-of-contents)

I've only used XGBoost it was the idea from the start, to only use XGBoost.

- XGBoost a powerful algorithm based on gradient boosted regularization.

## 📊 Visualization
[↑ Back to the table](#table-of-contents)

There only, important, visualization that there's in this project, is the sonar visualization, as to better help identify what it is that we're working with, we're given 60 attributes, but more than attributes, they're the different y-axis values that each x-axis position take. In other words, we're evaluating a signal, so, plotting it, can help us understand if our model is actually working correctly and, maybe, failing on similar signals, or it's completely messing the labeling.

## 🤓 Conclusions
[↑ Back to the table](#table-of-contents)

Whenever possible, even on a perfect, ready-to-work dataset, read the abstract, the paper, whatever information it is that you may have at hand, it truly helps understand the evaluation of the results and it's tuning.

And, once again, distribution can do wonders, having a distributed dataset is truly important, and if you don't have one, you can create it, undersampling is the best option around, unless you can actually create/collect reliable synthethic data, which is not the case.

## ©️ Credits
[↑ Back to the table](#table-of-contents)

The data set was contributed to the benchmark collection by Terry Sejnowski, now at the Salk Institute and the University of California at San Deigo. The data set was developed in collaboration with R. Paul Gorman of Allied-Signal Aerospace Technology Center.

But more information can be found at the [official datateset's paper](http://archive.ics.uci.edu/ml/datasets/connectionist+bench+(sonar,+mines+vs.+rocks)).