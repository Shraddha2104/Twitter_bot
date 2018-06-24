# Twitter_bot
A Python bot that automates several actions on Twitter, such as following users and favoriting tweets.

**Features**

* Update our twitter status from a text file<br />
* Automatically follow any users that have followed you<br />
* Automatically retweet any tweets that have a specific phrase<br />
* Automatically follow any users that tweet something with a specific phrase<br />
* Takes any image you tweet at it and randomly rearranges blocks of pixels of the image to create a new scrambled image and replies the tweet with the newly formed image.

## Dependencies

You will need to install Python's package:

    pip install twitter

You will also need to create an app account on https://dev.twitter.com/apps

1. Sign in with your Twitter account
2. Create a new app account
3. Modify the settings for that app account to allow read & write
4. Generate a new OAuth token with those permissions

Following these steps will create 4 tokens that you will need to place in the configuration file discussed below.


### Configuring the bot

Before running the bot, you must first set it up so it can connect to the Twitter API. Create a config.txt file and fill in the following information:

    OAUTH_TOKEN:
    OAUTH_SECRET:
    CONSUMER_KEY:
    CONSUMER_SECRET:
    TWITTER_HANDLE:
### How to run:

```shell
python twitterbot_retweet.py
python scramble.py
```
