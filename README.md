# Twitter_Bot
It's an automated Bot that responds to the tweets posted with my user name @Eshu_bade and #eswarbot or #eshwarbot

# Starting:

Install the 'tweepy' package in the command prompt based on the python version in your system.

Based on the python version, use the below links:

- For version Python 3.6:

pip3 install tweepy

- For version Python 3.7:

pip3 install -U git+https://github.com/tweepy/tweepy.git@2efe385fc69385b57733f747ee62e6be12a1338b

If the above command throws error, try replacing pip3 with pip, that should work fine!


# Files and contents

my_bot_Iham.py - The main file that has the code and the logic.

last_seen_id.txt - A text file to store the last seen ID of the tweet. If you see any error while running the main file, try inserting the ID of the tweets(ex:1388753791234589667) that you want to examine.

keys.py - The content in this file should not be used in the main file. Store this file in the same folder and fill the Access tokens and API keys of your developer account. The main code was writter in such a way that it would take the information from the keys.py and access it.
