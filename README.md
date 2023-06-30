# TwitchPlays
## What is new in the simplified version:
In an attempt to make it easier to use dougdoug's TwitchPlays script, I have forked it and put everything YOU can adjust in `SETUP_AND_START.py`.
You don't have to touch anything within the `TwitchPlays` folder.

Also, you can now add configurations for multiple games. For that, just copy the `template.py` file in the `Games` folder, name it however you want and adjust the content (e.g. keywords and behaviour) to your needs.
Then, put the file name of your newly created file into the `GAME_FILE_NAME` variable in the `SETUP_AND_START.py` file. (Without the `.py`, e.g. `GAME_FILE_NAME = "template"`).
You can have infinite game files and just swap between them by changing the aforementioned variable. The script has to be restarted to change the game.

## Original README by dougdoug (adjusted to my changes)
These are the Python files I use that allows Twitch Chat or YouTube Chat to control your keyboard or mouse to play a game. You are welcome to use or adapt this code for your own content.

To run the code you will need to install Python 3.9 or higher.  
Additionally, you will need to install the following python modules using Pip:  
python -m pip install keyboard  
python -m pip install pydirectinput  
python -m pip install pyautogui  
python -m pip install pynput  
python -m pip install requests  

Once Python is set up, simply change the Twitch username (or YouTube channel ID) in `SETUP_AND_START.py`, and you'll be ready to go.
The template game file are the original inputs from dougdoug's `TwitchPlays_TEMPLATE.py` file. Read "What is new in the simplified version" to learn how to add new games.

To run the script, you can simply double-click the `SETUP_AND_START.py` file in the Windows Explorer and open it with Python. Alternatively you can run it with an IDE (Integrated develeopment environment) such as [PyCharm](https://www.jetbrains.com/pycharm/download/?section=windows) or [Visual Studio Code](https://code.visualstudio.com/). These tools also make it easier to adjust the script to your needs. For PyCharm, make sure to download the Community Edition as the Professional one will cost money. 

This code is originally based off Wituz's Twitch Plays template, then expanded by DougDoug and DDarknut with help from Ottomated for the Youtube side. For now I am not reviewing any pull requests or code changes, this code is meant to be a simple prototype that is uploaded for educational purposes. But feel free to fork the project and create your own version!
