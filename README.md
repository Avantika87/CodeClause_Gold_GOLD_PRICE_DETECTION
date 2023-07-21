# CodeClause_Gold_GOLD_PRICE_DETECTION

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)<br>

## What It Does:
This ML or SML model uses historical data to forecast future price changes.It provide insights into whether gold price is likely to rise, fall or remain stable.It can be used by Analysts and investors to make informed decisions about buying, selling, or holding gold assets.However, predicting financial markets is complex and uncertain, so these models should be used alongside other analyses for more comprehensive decision-making.
 


1️⃣ Data Collection <br>
2️⃣ Data Preprocessing <br>
3️⃣ Data Wrangling <br>
4️⃣ Dataset Balancing & Scaling <br>
5️⃣ Machine Learning Model Training and Evaluation


## Prerequisites:
Before the hacknight, it is advised to have a ready-to-use toolchain and development environment.A recommended set of tools contains : <br>


1️⃣ `Python`<br>
2️⃣ `scikit-learn` / `sklearn`<br>
3️⃣ `Pandas`<br>
4️⃣ `NumPy`<br>
5️⃣ `Seaborn`<br>
6️⃣ `matplotlib` <br>
7️⃣ An environment to work in - something like  `colab` or `Jupyter` <br>


For Linux people, your package manager should be able to handle all of this. If it somehow can't, see if you can at least install Python and pip and then use pip to install the above packages.

## Dataset:

> You can collect raw dataset from [here](gld_price_data.csv).

Attribute Information:<br>
1️⃣ `Date` <br>
2️⃣ `SPX` <br>
3️⃣ `GLD` <br>
4️⃣ `USO` <br>
5️⃣ `SLV` <br>
6️⃣ `EUR/USD`<br>

## Machine Learning Model:

1️⃣`RANDOM FOREST`

 It is an ensemble learning algorithm capable of performing both regression and classification that combines several decision trees to make unique predictions.It includes random selection of data and features to train each tree individually.In classification tasks, the final prediction is made through majority voting, while in regression tasks, the predictions are averaged. It is best known for its:-
1.Robustness
2.Ability to handle large datasets
3.Provision of feature importance estimations.**
  <img title="a title" alt="Alt text" src="[/images/boo.svg](https://serokell.io/files/vz/vz1f8191.Ensemble-of-decision-trees.png)https://serokell.io/files/vz/vz1f8191.Ensemble-of-decision-trees.png">


