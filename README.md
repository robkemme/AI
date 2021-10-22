# AI
Building AI course project 

## Summary
Develop an AI application that analyzes multiple news items from different sources. The goal is to present a less biased view about a specific topic.  

## Background
As an example: I noticed that CNN and RT (Russia Today) can present the same news in a (very) different way. People should be made aware that there are often multiple ways to report and/or interpret 'facts'.

## How is it used?
* Gather multiple news items about a specific subject;
* Analyze the text to determine if the news is presented in a positive or negative way;
* Present a scoreboard with an overview of the news items, links to the websites where the news was found and a calculated score: very postive - positive - neutral - negative - very negative - undetermined. 

## Data sources and AI methods
Collect news items from internet (websites, twitter). Analyze text using Bayes rule.

## Challenges
News items in languages other than English. Not all news will be published in the English language. This means that the analyze algorith must either support multiple languages or the text must be translated into English before it can be analyzed.

## What next?
The next step could be machine learning to detect fake news and/or perform fact-checking.

## Acknowledgments
n/a

## Programming language 
The AI solution will be developed in Python.
