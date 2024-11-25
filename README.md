# SlackVitalAI
Building AI course project

## Summary
This project is meant to extract commonly asked questions from slack channels store them in a database so they can be answered by a bot before a new question is asked.
By utilizing this bot in your slack channel you can save your colleagues time which is stolen by task and context switching.
This will save time and money for organisations where users can focus on new questions and other assignments.

## Background
Very often questions are asked over and over in slack channels at offices but they occur every so often that it is hard to find just by scrolling history. It's also not that easy for new employees to find information in right places.

## How is it used?
Having this bot activated in your slack channel will make it possible to scrape history for selected channel.
When typing a question, the bot would suggest answers before questions are asked.

## Data sources and AI methods
Data source is the history of current channel. This is based nearest neighbor search to match questions asked in channels before.

## Challenges
The challenges are to keep questions relevant and how to differentiate between a question like "How do I genereate reports in system X?" from "What's on the lunch menu for today?" (Not that it would be insignificant but it doesn't add business value).
There might be problems keeping questions based on time relevant, they need to be updated from time to tima to stay relevant.

## Acknowledgments
Inspiration from the myriad of questions at previous work places.
