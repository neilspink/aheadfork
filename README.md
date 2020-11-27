# aheadfork

You found the perfect repository on GitHub with the source code to make your project work. However, it's not been maintained in some time. 

A lot of people forking the repository, perhaps someone has been fixing problems. 


The python script here helps you find all fork repositories that are ahead of original repo

# Prerequisite

- Before running, install requirement first: ```python3 -m pip install requests```
- You will need an [API access token for GitHub](https://docs.github.com/en/free-pro-team@latest/github/authenticating-to-github/creating-a-personal-access-token). 

# How to run

Usage: 
```
python3 aheadfork.py GITHUB_API_TOKEN REPO
```
eg.
```
python3 %s ab124942710137429ffdac322314701471234411 nkolban/esp32-snippets
```

Example repo  
https://github.com/nkolban/esp32-snippets  
https://github.com/nkolban/esp32-snippets/network/members
