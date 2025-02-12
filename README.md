# General information and criteria
This repo consists of economic and financial data (shared via my Google drive). The data here are shared based on the following criteria:
* The data set is based on textual data
* The data set is big
* The data is open-source

Now, let's the fun begin by finding all data here: https://drive.google.com/drive/folders/1qvTosJHrzonS10DdI0cjMS7EQiGW6gi7?usp=sharing

# List of data
### Attention and sentiment scores of accounting topics discussed in 10-K and 10-Q filings
1. The raw filings are downloaded from Loughran-McDonald webpage (https://sraf.nd.edu/sec-edgar-data/cleaned-10x-files/)
2. It consists of 890,277 observations of 41,552 US firms, identified by CIK number, ranging from 1994-01-01 to 2023-12-31. On average, a firm filed 21 times (quarterly) during the sample period
3. The data consists of the following fields (columns):
   * `cik`: the SEC identifier of firms;
   * `filing_date`: the date that a firm submits the corresponding filing to the SEC server;
   * `form`: the type of SEC forms that a firm submits;
   * `year`, `quarter`, `month`: the filing time, extracted from the `filing_date` column;
   * `<T_j>_attention`: the attention score of topic $T_j$ discussed in the corresponding filing. The higher this score is, the more the topic is discussed in this filing. This score is derived by a customized language model.
   * `<T_j>_sentiment`: the sentiment score of topic $T_j$ discussed in the corresponding filing. The higher this score is, the more positive the topic is discussed in this filing. This score is derived by a customized language model and FinBERT (Huang, et al., 2023)
4. The detailed description on how these attention and sentiment scores as well as several analyses are given in the folder **Attention and sentiment scores of accounting topics discussed in 10-K and 10-Q filings** of this repo
### _(to be updated)_

# Potential dataset to exploit
### US patents
1. Measuring innovation using the text body of patents
2. _(to be updated)_

# Personal message!
* If these dataset help you with your research, I am happy if you can buy me some coffee at https://buymeacoffee.com/minhtriphan
* If you have some ideas on how to exploit these data further or on which data you might want me to exploit (and those also complies with the above-mentioned criteria), please contact me via phanminhtri2611@gmail.com or triminh.phan@unibas.ch!
* I am also open to discuss research ideas with you!
