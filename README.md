# Selenium script to change Heroku accounts

This repository is a Python script using Selenium to automatize changing free dynos from two accounts from Heroku.

I made this script because I was too lazy to change between my two Heroku accounts in which I've hosted my 
[discord bot](https://github.com/RafaelBarrero/nibbler_bot), so I made and automatic script to do so.

This goes in conjunction with the [virtual assistant](https://github.com/RafaelBarrero/hue_voice_control)
I was programming, also in Python.

## Installation
Download this repository and install necessary dependencies with ```pip install -r .\requirements.txt```

## Usage
Change sampler credentials from ``settings.py`` with your own credentials and launch the script with
```
python .\src\main.py
``` 

If everything is alright, in about 30 seconds it would change dyno worker status from one account to another.