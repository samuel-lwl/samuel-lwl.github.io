

## Samuel's Portfolio
- [Sentiment Analysis of tweets with Deep Learning](#Sentiment-Analysis-of-tweets-with-Deep-Learning)
- [Exploring HDB resale prices](#exploring-hdb-resale-prices)
- [Outlier Detection in Product Matching](#outlier-detection-in-product-matching)
- [Predicting customer churn](#predicting-customer-churn)

---
<a id="Sentiment-Analysis-of-tweets-with-Deep-Learning"> </a>

## Sentiment Analysis of tweets with Deep Learning 🤖
![sent-analy](/images/sentiment-analysis.png)

<p align="center">
    <a href="https://nbviewer.org/github/samuel-lwl/samuel-lwl.github.io/blob/master/projects/Sentiment-Analysis-Deep-Learning.ipynb">Notebook available here</a>
</p>

In this project, I explored the Huggingface framework and fine-tuned a pre-trained distilBERT model to outperform the default Huggingface sentiment classification model on the task of sentiment analysis of tweets. The dataset used was the <a href="https://huggingface.co/datasets/sentiment140">Sentiment140</a> dataset. I also trained a bi-LSTM model in TensorFlow for comparison.

Lastly, I scraped twitter for recent tweets related to Elon Musk and used the fine-tuned transformer to predict their sentiments.

---

<a id="exploring-hdb-resale-prices"> </a>

## Exploring HDB resale prices
![HDB](/images/HDB.jpg)

<p align="center">
    <a href="https://nbviewer.jupyter.org/github/samuel-lwl/samuel-lwl.github.io/blob/master/projects/hdb-analysis.ipynb">Notebook available here</a>
</p>

In this project, I explored and visualised public housing resale prices using Plotly from 2017 to 2021 to learn about recent market trends - specifically, the impact of COVID on the market. I also analysed possible factors affecting resale prices. 

Supervised learning models were then trained on past data using Scikit-learn and PyTorch and tested on newer unseen transactions, achieving results less than 10% away from the true values on average. Lastly, unsupervised learning models were used to identify interesting patterns in the data by clustering transactions to form house segments.

---

<a id="outlier-detection-in-product-matching"> </a>

## Outlier Detection in Product Matching
![retail](/images/retail.png)

<p align="center">
    <a href="https://www.kaggle.com/samuellwl/outlier-detection-in-product-matching">Notebook available here</a>
</p>

In this short project, I attempted to detect outliers in product names using a combination of word processing techniques and a couple of unsupervised learning models with varying success.

---

<a id="predicting-customer-churn"> </a>

## Predicting customer churn
![churn](/images/churn.png)

<p align="center">
    <a href="https://www.kaggle.com/samuellwl/predicting-telco-customer-churn">Notebook available here</a>
</p>

This project involves predicting whether or not a customer is likely to leave a company. Several supervised learning models were trained and compared on their results, with the best model obtaining 80% accuracy.



