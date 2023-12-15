#installing tools
install Jupyter Notebook from command prompt

#importing the libraries
import numpy as np
import pandas as pd
import re
import pickle 
import nltk

#import NewsData.xlsx dataset from cd drive

#download glove840b300dtxt from given link
https://www.kaggle.com/takuok/glove840b300dtxt?fbclid=IwAR38BQqw4_qoa0FZvb5rXFBF5FAfAPkdRRsCBdQkd88GzsSHBb2FBx_WN-c

#download -GoogleNews-vectors from given link
https://github.com/mmihaltz/word2vec-GoogleNews-vectors?fbclid=IwAR2_P1h0HeVXfk9RAgAgoqzC84TJ5uVSDZNvlEb93QFO6uJ6_hjTtKc2OjQ

#description
Sports news site like www.newsnow.co.uk, www.90min.com, www.goal.com, www.express.co.uk, www.foxsports.com.au, www.espnfc.com, www.skysports.com, www.euronews.com have become extremely popular since their appearance and news. Today hundred of sports news portals site share their news about the club football player transfer.
In professional football, a transfer is the action taken whenever a player under contract moves between clubs. It refers to the transferring of a player's registration from one club to another. In general, the players can only be transferred during transfer window and according to the rules set by a governing body. In transfer window, before transfer of a player in a club we got many news from sports news agency about his transfer. So we collect these news as a data and we have to make a decision about his transfer possibility rate in a club using machine learning.

In this thesis, We researched the feasibility of using machine learning (ML), collection of training algorithms for classifying the chance of a transfer rate for football players. Research encompasses the whole process: data collection and note-up, extraction and engineering of the features, evaluation of the performance of the various algorithms.
