# Introduction

clis is stream viewer. The stream is formed of feeds, status updates, or anything is item by item in time sorting.

clis is not a feed reader. clis is not a client software of Twitter, FriendFeed, or anything. You can only read. clis is not an interactive program.

clis remembers (not all source types) last one it shows you, so after you restart clis, it won't show you stuff that you have read. It is new, many settings are just for testing, any ideas, suggestions are very welcome.

# Screenshots/casts

 * http://www.youtube.com/watch?v=0lU5IpHFoiE
 * http://friendfeed.com/livibetter/c67340f1/clis-is-my-new-twitter-tracker-image-on-top
 * http://friendfeed.com/livibetter/0c17b4f4/now-clis-has-local-url-shortening-goodbye-long
 * http://friendfeed.com/livibetter/0f40ad98/bigger-screenshot-of-clis
 * http://friendfeed.com/livibetter/54414d6b/oh-yeah-i-got-3-back

# Dependencies

 * [pyratemp](http://www.simple-is-better.org/template/pyratemp.html) (included)
 * [FeedParser](http://feedparser.org/)
 * [Official FriendFeed API library](http://code.google.com/p/friendfeed-api/) (included)
 * [python-oauth2](http://github.com/simplegeo/python-oauth2) for Twitter sources

# Supported Sources

 * Gmail: Mails in inbox
 * Google Reader: Items of subscriptions
 * Feed: Normal feed, RSS, atom, etc. Powered by [FeedParser](http://feedparser.org/)
 * FriendFeed: Home stream. Powered by [Official library](http://code.google.com/p/friendfeed-api/) with my modification in order to use real-time API.
 * Twitter: Shows statuses of you and whom you follow.
 * Twitter Mentions: Grab user's mentions feed.
 * Twitter Search: Search keywords on Twitter.
 * Weather: Shows current weather information from [weather.com](http://www.weather.com/).
 * PunBB 1.2: Special support for PunBB 1.2's feed.
 * Tail: Like doing tail -F filename
 * Craigslist: Same as Feed, it's made for dealing some feeds of Craigslist have few entries do not have published or updated dates, that causes those entries show up repeatly.

# Download

    git clone git@github.com:livibetter/clis.git

# Configuration

The default locations of configuration are (in order):

 1. `Current directory/clis_cfg.py`
 2. `Current directory/clis_cfg`
 3. `~/.clis_cfg.py`
 4. `~/clis_cfg.py`

Please copy `clis_cfg-sample.py` and move to location at one above, or you can run with `./clis.py -c /path/to/conf_file`.

# Commands

Press `<Enter>` to enter command mode, you will see `Command>` prompt, then:

 * `<Enter>`: Print a separator
 * `reload`: Reload configuration
 * `clear`: Clear the screen
 * `quit`: Quit clis
 
# Support

Feel free to ask your question in [discussion group](http://groups.google.com/group/yu-jie-lin).
