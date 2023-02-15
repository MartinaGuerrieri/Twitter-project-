# Twitter-project-
## Project 1: Can we learn from Twitter Data?

---

### Problem:

We need a process that allows us automatically scrape Twitter for conversations on one or more topics of our choice.

We should be able to return the most frequent words used in the various topics and represent this in a visual method for the admin (IL, Speaker, or TA) to see on their computers.

### Scope:

1. Determine the scope of topics with the IL.
2. Determine the scope of tweets to fetch with the IL.
3. Determine your programming process scope with your team and validate with the IL.
4. Determine output scope for the user with your team and IL.

### Expected Solution:

1. Data Engineering Solution:
    1. A python set of processes that can fetch data from Twitter, clean it within the scope of your team's expectations, arrange it in tables, and store the data in a local SQLite database, MongoDB instance, or a local CSV.
2. Data Analysis Solution:
    1. A python set of processes that can receive user input regarding the type of analysis to be done, fetch cleaned Twitter data regarding a topic from a database or a CSV file, and produce a visual representation of the analysis that was done.
