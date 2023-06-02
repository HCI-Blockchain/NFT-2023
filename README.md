# On the Mechanics of NFT Valuation: AI Ethics and Social Media

## Supplementary resources, data, and code
by **Luyao Zhang***, **Yutong Sun**, **Yutong Quan**, **Jessie Cao** and **Xin Tong***

(* *corresponding authors*)

## Table of Contents
- [Data](https://github.com/HCI-Blockchain/NFT-2023#data)
- [Code](https://github.com/HCI-Blockchain/NFT-2023#code)
- [Image](https://github.com/HCI-Blockchain/NFT-2023#image)

## Data
### Collected Data
| **File Name** | **Data Category** | **Discription** |
|--|--|--|
| queried_tweets_cryptopunk_2017_2022.csv  | Social Media Data | All CryptoPunks-related tweets |
| tweets_cryptopunk_gender_skintone.csv | Social Media Data | Tweets related to gender and skin tone in CryptoPunks |
| cryptopunks_gender_skintone_info_new.csv | Transaction Data | CryptoPunks general information including skin tone, gender, price (in ETH), and trading wallet address |
| Ethereum Gas Price_Daily Average.csv | Transaction Data | Ethereum daily average gas price |
| ETH_USD.csv | Transaction Data | The ETH/USD exchange rate |

### Analyzed Data
| **File Name** | **Discription** | **Section of Paper** |
|--|--|--|
| analyzed_tweet_volume_cryptopunk_2017_2022.csv  | Daily tweet volume of CryptoPunks from 2017 to 2022 | 4.1.1 Twitter Sentiment Analysis |
| analyzed_sentiment_cryptopunk_2017_2022.csv | Daily sentiment score of CryptoPunks from 2017 to 2022 | 4.1.1 Twitter Sentiment Analysis |
| analyzed_gender_skintone_transaction data.csv | The number and proportion of CryptoPunks traded from 2017 to 2022 according to gender and skin tone information | 4.1.2 Gender and Skin Tone Analysis of Transaction Data |
| analyzed_keyword_sentiment and frequency.csv | Word frequency and sentiment score of gender and skin tone keywords in Tweets | 4.1.3 Twitter Discussion Analysis of Ethical Keywords |

## Code
| **Content** | **Section of Paper** | **URL** |
|--|--|--|
| CryptoPunks Twitter Data Collection | 3.1. Data Collection | https://github.com/HCI-Blockchain/NFT-2023/blob/main/code/query/twitter/Twitter_Query_CryptoPunks.ipynb |
| CryptoPunks Twitter Sentiment Analysis | 4.1.1 Twitter Sentiment Analysis | https://github.com/HCI-Blockchain/NFT-2023/blob/main/code/analyze/social%20media%20analysis/Sentiment_Analysis_CryptoPunks.ipynb |
| CryptoPunks Transaction Gender and Skin Tone Analysis | 4.1.2 Gender and Skin Tone Analysis of Transaction Data | https://github.com/HCI-Blockchain/NFT-2023/blob/main/code/analyze/transaction%20data%20visualization/Transaction_Data_Analysis_CryptoPunks_Gender_Skin_tone.ipynb |
| Word Frequency and Sentiment Analysis of Twitter Ethical Keywords | 4.1.3 Twitter Discussion Analysis of Ethical Keywords | https://github.com/HCI-Blockchain/NFT-2023/blob/main/code/analyze/social%20media%20analysis/Twitter_Analysis_CryptoPunks_Gender_Skin_tone.ipynb |
| Hedonic Regression | 4.2. The Influence of CryptoPunks Twitter Sentiment to CryptoPunks Valuation & 4.3. The Structural Changes in CryptoPunks Valuation After 2021 | https://github.com/HCI-Blockchain/NFT-2023/blob/main/code/Regression/Hedonic%20Regression_skin_gender_sentiment.ipynb |
| Regression Result Visualization (Lollipop Plot) | 4.2. The Influence of CryptoPunks Twitter Sentiment to CryptoPunks Valuation & 4.3. The Structural Changes in CryptoPunks Valuation After 2021 | https://github.com/HCI-Blockchain/NFT-2023/blob/main/code/analyze/hedonic%20regression/Lollipop_plot_Hedonic_Regression.ipynb |

## Data Visualization
- [image](https://github.com/HCI-Blockchain/ICWSM-2023/tree/main/code/figure)
