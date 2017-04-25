# datascience
The SemEval-2016 dataset was downloaded using their recommended python script for Natural Language Processing (NLP) task of Sentiment Analysis. The instructions can be downloaded from https://github.com/aritter/twitter_download. I had to comment line 36 in download_tweets_api.py because script was crashing. 
'''Python
#uid = fields[1]
'''
The raw downloaded dataset stats are:

Environment | Task | Point |  number of Tweets
------------|------|-------|--------------------
DEV         | A    | Three |	2000
DEV         | B,D  | Two   | 	1325
DEV         | C,E  | Five  | 	2000
DEV_TEST    | A    | Three | 	2000 
DEV_TEST    | B,D  | Two   | 	1417
DEV_TEST    | C,E  | Five  | 	2000
TRAIN       | A    | Three |	6000
TRAIN       | B,D  | Two   | 	4346
DTRAINEV    | C,E  | Five  | 	6000
