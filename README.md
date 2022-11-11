# Rasa-demo-project
Using Rasa to crate a simple bot (Greek language) 
RASA HOW TO: 

Installation:
•	I used Anaconda PowerShell Prompt. (Otherwise you have to install python 3.6<version<3.9)
•	Make sure “Visual Studio Build Tools” is installed
  If not,
  Then download Microsoft Visual C++ 14 and install the compiler. 
•	pip3 install -U pip (or pip install -U pip)
•	pip3 install rasa (or pip install rasa) (It is also recommended to create a virtual environment… I didn’t.)

Create a Rasa project:
•	Create a file and then using the “cd” command go to the created file through anaconda terminal
•	Then on your terminal run the command: rasa init

Rasa Project main files: 
•	nlu.yml
•	stories.yml
•	rules.yml
•	domain.yml
•	config.yml
You can see them in your Rasa project you just created with the “rasa init” command.
I opened those yml files through VSCode.

Train a Rasa model:
•	Use the command “rasa train” to train your model

Chat with the bot:
•	Use the command “rasa shell” and then add your input to your terminal and wait for the bot to answer.

Rasa documentation:
•	https://rasa.com/docs/rasa/
