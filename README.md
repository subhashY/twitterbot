# Twitter Bot

A sample twitter bot in ython



#### If you have Python 3.6, you can just run:

``pip3 install tweepy``

#### If you have Python 3.7, run the following instead:

``pip3 install -U git+https://github.com/tweepy/tweepy.git@2efe385fc69385b57733f747ee62e6be12a1338b``

If the above command doesn't work, try replacing ``pip3`` with ``pip`` also.

#### If you have Python 3.7 and want to use pipenv, use:

``pipenv install -e git+https://github.com/tweepy/tweepy.git@2efe385fc69385b57733f747ee62e6be12a1338b#egg=tweepy``

---

## Files
- **my_twitter_bot.py** - This is the main file that includes all the logic.
- **last_seen_id.txt** - This will contain the ID of the tweet that my_twitter_bot.py has seen last. If you see any errors when running the main file, try replacing the content with the ID of one of the tweets you want to examine.
- **keys_format.py** - This file is not meant to be used directly. Instead, copy this file in the same folder and rename it to keys.py. Then, put your Twitter API keys in keys.py. That way, my_twitter_bot.py will be able to use this information.