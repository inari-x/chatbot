# chatbot
Chatbot for uni project. This is a PyCharm project. 


# Dependencies
- Python 3.6
- Flask

# Instructions

Activate virtual environment 

>> `katsch$ source venv/bin/activate`

for python development

Open terminal, `python chat.py`

Check @ http://localhost(:80)/

# Changelog
v0.0.1 - Halloween, 2022

## What is it?
## This project is a chatbot that can be used to ask simple questions about machine learning, AI and bias in computer systems. The bot is based on the language python and a bit of machine learning. It has a confidence level, once set up closer to 1 it will just reply what you told it to. The "brain" of the bot is in the /data/chatbot.csv file. For the deployment of the project pythonanywhere.com was used. Requirements are listed in the requirements.txt file.

## How does it work?
## Keplie learns from the data in the chatbot.csv file. The data is structured in a way that the first column is the input and the second column is the output. The bot will learn from the data and will be able to answer questions based on the data. The bot is not able to learn from new data, it is just able to answer questions based on the data it has. The more people interact with kelpie, the more it will learn. The second methode to make Kelpie better is to talk to him and later change his answers in the trainlog.py file. You can do that by just stopping the bot and run in the terminal: "python trainlog.py". This will open a file where you can change the answers.
## In the static folder you can change the whole layout of the bot. 

## Functions
## getTime() - returns the current time
## getDate() - returns the current date
## getDay() - returns the current day
## Idknull() - returns a random answer from the list

## Setup
## demo.py - this file is used to test the bot
## chat.py - this file is used to run the bot
## trainlog.py - this file is used to change the answers of the bot
## chatbot.csv - this file is used to train the bot
## Botlog.csv - this file is used to log the conversations
## botRespond.py - this file is used to make the bot respond
## dateTime.py - this file is used to get the date, time and day --> functions
## button.py - this file is used to make the bot respond to buttons
## requirements.txt - this file is used to install the dependencies

## How to use it?
## You can use the bot by going to the website: https://kelpie.eu.pythonanywhere.com/ or by running the chat.py file in your terminal.

## How to contribute?
## You can contribute by adding more data to the chatbot.csv file. You can also contribute by changing the answers in the trainlog.py file. You can also contribute by adding more features to the bot.

## How to report bugs?
## You can report bugs by creating an issue on github. You can also report bugs by sending an email to: katrinmalfent@gmail.com






