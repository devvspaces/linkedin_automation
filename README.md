# Linkedin Message Automation
> This linkendin automation script allows one to add links of linkedin profiles you want to connect to and the bot automatically logs in on your account and send provided message to connects and connects with them. Currently commands are passed with a list of dictionaries. This project uses selenium for web scraping and automation. I got the inspiration to work on this while working on my discord bot application [Discord Bot](https://github.com/devvspaces/discordbot). I learnt a lot about email services and seamless web automation while working on this project.

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/devvspaces/linkedin_automation/graphs/commit-activity)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/devvspaces/linkedin_automation/issues)



## Requirements  (Prerequisites)
Tools and packages required to successfully install this project.
For example:
* Python 3.3 and up [Install](https://www.python.org/downloads/)


## Installation
A step by step list of commands / guide that informs how to install an instance of this project. 

First setup python virtual environment (optional but good)
```sh

pip install virtualenv

virtualenv venv # Create the virtual environment

source venv/bin/activate # For linux systems

venv/Scripts/activate # For Windows systems

```

Install project dependencies

`$ pip install -r requirements.txt`

Start Automation

`$ python linkedin.py`


## Features
* Used Selenium and IMAP to make it 100% automated
* Used a class for selenium driver to make it object oriented in design
* The class has different methods that you can reuse or add to

## Usage example
It is simple to use, just install package and edit the connects list, add new connects dictionary and run linkedin.py
```python
connects = [
    {
        'link': 'https://www.linkedin.com/in/xxxxxxx',
        'note': 'Add your note here'
    }
]
```


## Tech Stack / Built With
1. Python only

## How to Contribute

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change. Please make sure to update tests as appropriate. If you'd like to contribute, please fork the repository and make changes as you'd like. Pull requests are warmly welcome.

Steps to contribute:
1. Fork this repository (https://github.com/devvspaces/linkedin_automation)
2. Create your feature branch (git checkout -b feature/fooBar)
3. Commit your changes (git commit -am 'Add some fooBar')
4. Push to the branch (git push origin feature/fooBar)
5. Create a new Pull Request

## Authors
 
Ayanwola Ayomide – sketcherslodge@gmail.com

I love programming with python but also uses JavaScript and php on client side to create more dynamic applications.
 
You can find me here at:

[Github](https://github.com/devvspaces)

[LinkedIn](https://www.linkedin.com/in/netrobe-webby-878920194/)

## Credits
I give credits to the wonderful developers in StackoverFlow and online for being the building block for the success of this project, I love you all. ;-)
