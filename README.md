# ai-bot-mechy
Mechy is an AI bot which will be able to search its own database for common vehicle problems like repairing a flat tire, vehicle stuck in mud, overheating engine etc. The bot will be able to provide the user with the tools to use and the procedures to follow to tacke the issue.
For larger emergencies, the bot will provide the contact details of emergency roadside assistance, to help tow the car. While listing out the tools and the procedure, the bot will move on to the next instruction only after user acknowledgment. It will also have the option to repeat the same procedure or go back to the last procedure. The application is currently a web application built using Javascript and HTML/CSS and uses api.ai for NLU module.

# Prequistes
Need an apache server to run it on the local host

# Installing apache
On an Unix/ macOS machine, run the following in terminal to start the server :
sudo apachectl start

Copy the index file on to the following address on your machine:
/Library/WebServer/Documents/ on macOS

Go to your browser and type the localhost address:
http://127.0.0.1

# Deployment
This application can be deployed on Heroku or other services using AWS like EC2

# Built with
Language processing with api.api NLU,
Front-end HTML/CSS,
Backend Javascript,

# Future work
Introducing angular framework for Frontend,
Introducing Mongo for the database use,
Introducing a new feature where user can initiate the process by saying MECHY.
