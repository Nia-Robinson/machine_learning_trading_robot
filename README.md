# Project Title: Machine Learning Trading Robot

# Background
In this Challenge, you’ll assume the role of a financial advisor at one of the top five financial advisory firms in the world. Your firm constantly competes with the other major firms to manage and automatically trade assets in a highly dynamic environment. In recent years, your firm has heavily profited by using computer algorithms that can buy and sell faster than human traders.

The speed of these transactions gave your firm a competitive advantage early on. But, people still need to specifically program these systems, which limits their ability to adapt to new data. You’re thus planning to improve the existing algorithmic trading systems and maintain the firm’s competitive advantage in the market. To do so, you’ll enhance the existing trading signals with machine learning algorithms that can adapt to new data.

# What You're Creating
You’ll combine your new algorithmic trading skills with your existing skills in financial Python programming and machine learning to create an algorithmic trading bot that learns and adapts to new data and evolving markets.

In a Jupyter notebook, you’ll do the following:

Implement an algorithmic trading strategy that uses machine learning to automate the trade decisions.

Adjust the input parameters to optimize the trading algorithm.

Train a new machine learning model and compare its performance to that of a baseline model.

Dataset:
---
emerging_markets_ohlcv.csv

## Summary Evaluation Report

Support Vector Machine (SVM) Baseline (3 months; long SMA = 100): The model became unsteady around mid 2018 and increased above the actual returns.

![svm_baseline_3_months](https://user-images.githubusercontent.com/34729547/206221771-a62c9bb6-336f-493d-a2e7-a31c0b31c825.PNG)

SVM Baseline (6 months; long SMA = 100): The model became unsteady around 2019 and decreased below the actual returns when the training window increased.

![svm_baseline_6_months](https://user-images.githubusercontent.com/34729547/206223365-81c70223-d538-45b1-aed3-4ca8f0a48174.PNG)

SVM Baseline (6 months; long SMA = 200): The model became unsteady around mid 2017 and decreased below the actual returns when the long SMA increased.

![svm_baseline_6_months_50_200_sma](https://user-images.githubusercontent.com/34729547/206224355-bade7c5c-6ec1-45a8-831c-2d8c0303ca98.PNG)

SVM Baseline (6 months; long SMA = 85): The model remained steady and accurate when the long SMA was decreased while the training window increased.

![svm_baseline_6_months_50_85_sma](https://user-images.githubusercontent.com/34729547/206224798-746296e1-0650-4d8b-8928-5e306d50dc2e.PNG)

Logistic Regression Baseline (3 months; long SMA = 100): The model became unsteady around 2018 and increased above the actual returns; the returns are better in the LR model vs. SVM.

![lr_baseline_3_months](https://user-images.githubusercontent.com/34729547/206227114-82ea808c-18e9-47d6-841b-51a20767e883.PNG)


## Technologies: Python 3, Jupyter Notebook
---
Python 3 or later.

Jupyter Notebook for IDE.

---

## Usage:
---

Ensure the proper libraries and dependencies have been imported.

![image](https://user-images.githubusercontent.com/34729547/206221484-155a7b38-780b-4189-a494-91e2262a4601.png)

---

## Contributors: Nia Robinson

LinkedIn: https://www.linkedin.com/in/niaelanrobinson/

---

## License

MIT License.
