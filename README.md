# PCHGmail
Code for Analysis of a Gmail Mbox

This project documents how I worked through an entire data analysis in Python.

The subject is the Drexel University Peer Counseling Helpline's Gmail that I was able to export and load into Python using the `mailbox` package. I then ran simple summary statistics, and used the `matplotlib` and `seaborn` packages to find out a number of interesting things about how the Helpline has run in previous years, how many counselors we have at a time, the metrics about our calls, and using Python's Natural Language Tool Kit and regular expressions, what words and skills are used in our calls.

I also experimented with the Latent Dirichlet Allocation algorithm from the `gensim` package, to run and visualise topic modeling on the call logs.

In addition to learning a great deal about Pythonic programming and practice, I also found out a great deal about:
* Jupyter
* Dates & times in Python
* The power of regex
* Simple NLP
* Latent Dirichlet Allocation
* The power of Pandas

You can read the more verbose (and insightful) walkthrough on my Quora blog [here](https://dataintensive.quora.com/Data-Dive-The-Peer-Counseling-Helpline-Gmail-Archive)
