# On the Mechanics of NFT Valuation: AI Ethics and Social Media

[![DOI](https://zenodo.org/badge/585154437.svg)](https://zenodo.org/badge/latestdoi/585154437)

## *Supplementary resources, data, and code*
by **Luyao Zhang***, **Yutong Sun**, **Yutong Quan**, **Jessie Cao** and **Xin Tong***

(* *corresponding authors*)

### Datasets on Harvard Dataverse:

Zhang, Luyao; Yutong Sun; Yutong Quan; Jiaxun Cao; Tong Xin, 2023, "Replication Data for: On the Mechanics of NFT Valuation: AI Ethics and Social Media", https://doi.org/10.7910/DVN/YMZC30, Harvard Dataverse, V2, UNF:6:K18EFjOhNtecu0xnrmB6Wg== [fileUNF]


```
@data{DVN/YMZC30_2023,
author = {Zhang, Luyao and Yutong Sun and Yutong Quan and Jiaxun Cao and Tong Xin},
publisher = {Harvard Dataverse},
title = {{Replication Data for: On the Mechanics of NFT Valuation: AI Ethics and Social Media}},
UNF = {UNF:6:K18EFjOhNtecu0xnrmB6Wg==},
year = {2023},
version = {V2},
doi = {10.7910/DVN/YMZC30},
url = {https://doi.org/10.7910/DVN/YMZC30}
}

# Table of Contents

## Data
### [Collected Data](https://github.com/HCI-Blockchain/NFT-2023/tree/main/data/queried_data)
| **File Name** | **Data Category** | **Discription** |
|--|--|--|
| queried_tweets_cryptopunk_2017_2022.csv  | Social Media Data | All CryptoPunks-related tweets |
| tweets_cryptopunk_gender_skintone.csv | Social Media Data | Tweets related to gender and skin tone in CryptoPunks |
| cryptopunks_gender_skintone_info_new.csv | Transaction Data | CryptoPunks general information including skin tone, gender, price (in ETH), and trading wallet address |
| Ethereum Gas Price_Daily Average.csv | Transaction Data | Ethereum daily average gas price |
| ETH_USD.csv | Transaction Data | The ETH/USD exchange rate |


```

### [Analyzed Data](https://github.com/HCI-Blockchain/NFT-2023/tree/main/data/analyzed_data)
| **File Name** | **Discription** | **Section of Paper** |
|--|--|--|
| analyzed_tweet_volume_cryptopunk_2017_2022.csv  | Daily tweet volume of CryptoPunks from 2017 to 2022 | 4.1.1 Twitter Sentiment Analysis |
| analyzed_sentiment_cryptopunk_2017_2022.csv | Daily sentiment score of CryptoPunks from 2017 to 2022 | 4.1.1 Twitter Sentiment Analysis |
| analyzed_gender_skintone_transaction data.csv | The number and proportion of CryptoPunks traded from 2017 to 2022 according to gender and skin tone information | 4.1.2 Gender and Skin Tone Analysis of Transaction Data |
| analyzed_keyword_sentiment and frequency.csv | Word frequency and sentiment score of gender and skin tone keywords in Tweets | 4.1.3 Twitter Discussion Analysis of Ethical Keywords |
| merged dataset_without_sentiment.csv | Merged dataset for regression without sentiment score | 4.3. The Structural Changes in CryptoPunks Valuation After 2021 |
| merged dataset_with_sentiment.csv | Merged dataset for regression with sentiment score | 4.2. The Influence of CryptoPunks Twitter Sentiment to CryptoPunks Valuation & 4.3. The Structural Changes in CryptoPunks Valuation After 2021 |

## Code
| **Content** | **Section of Paper** | **URL** |
|--|--|--|
| CryptoPunks Twitter Data Collection | 3.1. Data Collection | https://github.com/HCI-Blockchain/NFT-2023/blob/main/code/query/twitter/Twitter_Query_CryptoPunks.ipynb |
| CryptoPunks Twitter Sentiment Analysis | 4.1.1 Twitter Sentiment Analysis | https://github.com/HCI-Blockchain/NFT-2023/blob/main/code/analyze/social%20media%20analysis/Sentiment_Analysis_CryptoPunks.ipynb |
| CryptoPunks Transaction Gender and Skin Tone Analysis | 4.1.2 Gender and Skin Tone Analysis of Transaction Data | https://github.com/HCI-Blockchain/NFT-2023/blob/main/code/analyze/transaction%20data%20visualization/Transaction_Data_Analysis_CryptoPunks_Gender_Skin_tone.ipynb |
| Word Frequency and Sentiment Analysis of Twitter Ethical Keywords | 4.1.3 Twitter Discussion Analysis of Ethical Keywords | https://github.com/HCI-Blockchain/NFT-2023/blob/main/code/analyze/social%20media%20analysis/Twitter_Analysis_CryptoPunks_Gender_Skin_tone.ipynb |
| Hedonic Regression | 4.2. The Influence of CryptoPunks Twitter Sentiment to CryptoPunks Valuation & 4.3. The Structural Changes in CryptoPunks Valuation After 2021 | https://github.com/HCI-Blockchain/NFT-2023/blob/main/code/analyze/hedonic%20regression/Hedonic%20Regression_skin_gender_sentiment.ipynb |
| Regression Result Visualization (Lollipop Plot) | 4.2. The Influence of CryptoPunks Twitter Sentiment to CryptoPunks Valuation & 4.3. The Structural Changes in CryptoPunks Valuation After 2021 | https://github.com/HCI-Blockchain/NFT-2023/blob/main/code/analyze/hedonic%20regression/Lollipop_plot_Hedonic_Regression.ipynb |

## [Data Visualization](https://github.com/HCI-Blockchain/NFT-2023/tree/main/figure)
### Section 4.1.1 Twitter Sentiment Analysis
**Fig.1: CryptoPunks daily tweet volume**
![CryptoPunks Daily Tweet Volume](https://github.com/HCI-Blockchain/NFT-2023/blob/main/figure/cryptopunks_daily_tweet_volume_2022.png)

**Fig.2: CryptoPunks daily sentiment score**
![CryptoPunks Daily Sentiment Score](https://github.com/HCI-Blockchain/NFT-2023/blob/main/figure/cryptopunks_daily_sentiment_2022.png)

**Fig.3: CryptoPunks sentiment distribution (days)**
![CryptoPunks Sentiment Distribution (Days)](https://github.com/HCI-Blockchain/NFT-2023/blob/main/figure/cryptopunks_sentiment_distribution_2022.png)

### Section 4.1.2 Gender and Skin Tone Analysis of Transaction Data
**Fig.4: CryptoPunks gender and skin tone distribution heatmap**
![CryptoPunks Gender and Skin Tone Distribution Heatmap](https://github.com/HCI-Blockchain/NFT-2023/blob/main/figure/CryptoPunks%20Gender%20and%20Skin%20Tone%20Distribution%20Heatmap_new.png)

### Section 4.1.3 Twitter Discussion Analysis of Ethical Keywords
**Fig.5: Word frequency of gender and skin tone keywords in tweets**
![Word Frequency of Gender and Skin Tone Keywords in Tweets](https://github.com/HCI-Blockchain/NFT-2023/blob/main/figure/Word%20Frequency%20of%20Gender%20and%20Skin%20Tone%20Keywords%20in%20Tweets.png)

**Fig.6: Sentiment scores for gender and skin tone keywords**
![Sentiment Scores for Gender and Skin Tone Keywords](https://github.com/HCI-Blockchain/NFT-2023/blob/main/figure/Sentiment%20Scores%20for%20Gender%20and%20Skin%20Tone%20Keywords.png)

### Section 4.2. The Influence of CryptoPunks Twitter Sentiment to CryptoPunks Valuation
**Fig.7: The comparison of the performance of price predictors (with and without sentiment
score)**
![The Comparison of the Performance of Price Predictors (With and Without Sentiment
Score)](https://github.com/HCI-Blockchain/NFT-2023/blob/main/figure/lollipop_sentiment.png)

### Section 4.3. The Structural Changes in CryptoPunks Valuation After 2021
**Fig.8: The comparison of the performance of price predictors (before and after 2021)**
![The Comparison of the Performance of Price Predictors (Before and After 2021)](https://github.com/HCI-Blockchain/NFT-2023/blob/main/figure/lollipop_time.png)


