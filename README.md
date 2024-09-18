# Seoul Bike Demand Prediction 🚲

A comprehensive study of bike demand trends in the busy city of Seoul, capital of South Korea. The analysis utilizes techniques like EDA and regression analysis to predict bike demand rates which are impacted by various factors.

## Problem Statement
How can we effectively predict bike rental demand by leveraging factors such as predicted weather, time of year, and time of day, to ensure an optimal balance of available bikes and meet customer demand?

> More details in [`analysis.ipynb`](/notebook/analysis.ipynb).

### Results
![eval.png](/images/eval.png)

## Usage

Clone the repository and navigate to the root folder.

```bash
$ git clone <repo-link>
$ cd seoul-bike-demand
```

Create a `virtualenv` and install the required dependencies mentioned in `requirements.txt`.

```bash
$ virutalenv env
$ source env/bin/activate
$ python -m pip install -r requirements.txt
```

Navigate to the `notebook` directory and lauch jupyter lab.

```
$ cd notebook
$ jupyter lab
```

## Acknowledgements

The dataset has been retrieved from [Kaggle](https://www.google.com/url?q=https%3A%2F%2Farchive.ics.uci.edu%2Fdataset%2F560%2Fseoul%2Bbike%2Bsharing%2Bdemand).

## Contributions

Feel free to open up an issue or a pull request if you think the code needs some changes.
