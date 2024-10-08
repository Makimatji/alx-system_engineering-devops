#0x16. API advanced

Requirements
General
Allowed editors: vi, vim, emacs
All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.4.3)
All your files should end with a new line
The first line of all your files should be exactly #!/usr/bin/python3
Libraries imported in your Python files must be organized in alphabetical order
A README.md file, at the root of the folder of the project, is mandatory
Your code should use the PEP 8 style
All your files must be executable
The length of your files will be tested using wc
All your modules should have a documentation (python3 -c 'print(__import__("my_module").__doc__)')
You must use the Requests module for sending HTTP requests to the Reddit API

Tasks 📃
0. How many subs?

0-subs.py: Python function that returns the total number of subscribers for a given subreddit.
Returns 0 if an invalid subreddit is given.
1. Top Ten

1-top_ten.py: Python function that prints the top ten hottest posts for a given subreddit.
Prints None if an invalid subreddit is given.
2. Recurse it!

2-recurse.py: Python function that recursively returns a list of titles for all hot articles on a given subreddit.
Returns None if no results are found on the given subreddit.
3. Count it!

100-count.py: Python function that recursively prints a sorted count of given keywords parsed from titles of all hot articles on a given subreddit.
Keywords are case-insensitive and delimited by spaces.
Results are printed in descending order by count.
Words with identical counts are sorted alphabetically.
Words with no matches are skipped.
Results are based on the number of times a keyword appears - ie., java java java counts as three separate instances of java.
