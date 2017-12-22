# datascience
The SemEval-2016 dataset was downloaded using their recommended python script for Natural Language Processing (NLP) task of Sentiment Analysis. The instructions can be downloaded from https://github.com/aritter/twitter_download. I had to comment line 36 in download_tweets_api.py because script was crashing. 
```python
#uid = fields[1]
```
The raw downloaded dataset stats are:

Environment | Task | Point |  number of Tweets
------------|------|-------|--------------------
DEV         | A    | Three |	2000
DEV_TEST    | A    | Three | 	2000 
TRAIN       | A    | Three |	6000
TEST        | A    | Three |	20,633
DEV         | B,D  | Two   | 	1325
DEV_TEST    | B,D  | Two   | 	1417
TRAIN       | B,D  | Two   | 	4346
TEST        | B,D  | Two   | 	10,552
DEV         | C,E  | Five  | 	2000
DEV_TEST    | C,E  | Five  | 	2000
TRAIN       | C,E  | Five  | 	6000
TEST        | C,E  | Five  | 	20,632