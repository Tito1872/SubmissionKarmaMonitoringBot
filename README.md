# SubmissionKarmaMonitoringBot

Put your client ID, secret, reddit account username and password in praw.ini file while looks like this

```
[bot]  
client_id=  
client_secret=  
password=  
username=  
user_agent="Bot by u/Vault-TecTradingCo"
```

Also, in main.py file put the subreddit you want to run this bot on. Put the name without r/

```
subreddit = reddit.subreddit("subredditname")  # put subreddit name here
```

Put the name without "r/". For example, if someone wants to run the bot on memes. They would write

```
subreddit = reddit.subreddit("memes")  # put subreddit name here
```