# SpamDetectorAI
SpamDetectorAI is a tool for detecting spam words in emails or text messages.
Here is a tutorial:
```
from SpamDetectorAI import spamfilter as spamdetector
#Create a filter
spamfilter = spamdetector.SpamFilter()
#Report a spam message
spamfilter.report_spam(message="|MESSAGE|", keyword="|KEYWORD|", spammer="|SPAMMER|")
#Check if a message is spam
spamfilter.check_spam(text="|MESSAGE|")
```
