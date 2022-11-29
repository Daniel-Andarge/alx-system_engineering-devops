# Project 0x16. API advanced 📚

### 📋 Requirements
***
* Allowed editors: `vi`, `vim`, `emacs`
* Files will be interpreted/compiled on Ubuntu `14.04` LTS using `python3` (version `3.4.3`)
* Files must be executable
* The length of your files will be tested using `wc`
* You must use the Requests module for sending HTTP requests to the Reddit API
* Libraries imported in your Python files must be organized in alphabetical order
* The first line of all your files should be exactly `#!/usr/bin/python3`

### 🎨 Style
***
* Code should use the `PEP 8` style.

### 🎯 Tasks
***
Mandatory:
| Files | Description |
| --- | --- |
| [0-subs.py]() | Function that queries the Reddit API and returns the number of subscribers (not active users, total subscribers) for a given subreddit. If an invalid subreddit is given, the function should return 0. |
| [1-top_ten.py]() | Function that queries the Reddit API and prints the titles of the first 10 hot posts listed for a given subreddit. |
| [2-recurse.py]() | Recursive function that queries the Reddit API and returns a list containing the titles of all hot articles for a given subreddit. If no results are found for the given subreddit, the function should return None. |
