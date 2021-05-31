# Farkle in the Terminal
* This is a terminal version of the dice game Farkle. In order to use this repo, you must have Git and Poetry installed on your computer. If you do not have those installed, you can install them with Homebrew with the following commands: brew install git, and brew install poetry. If you do not have Homebrew installed, instructions can be found by clicking [here](https://docs.brew.sh/Installation). 

* clone this repo to your local computer, navigate to the directory where you want it to be located in. enter the following command: git clone https://github.com/zachhornung/game-of-greed.git. Enter the command: cd game-of-greed, and then enter the command: poetry install. Dependencies will then be installed, and you can next activate the virtual environment by typing the command: poetry shell. After the virtual environment has been activated, enter the following command to play the game: python game_of_greed/game.py.

* There are also bots on this repo that you can program to play the game in a particular way. To see the default bot's score, type the following command: python bots.py. The output will be the average score over 1000 games played. To adjust the behavior of the bot, open the bots.py file in your favorite editor and scroll to the bottom of the file. Follow the formatting for NervousNellie. If you wish to make a new bot, just make a new class that inherits from the class BaseBot, and after the line "if __name__ == "__main__":" insert \<nameofclasshere>.play(num_games). Run the bots.py file again and you will see the average score of your bot over the specified number of games. If you wish to change the number of games, simply change the number assigned to the variable num_games, save, and rerun the file.

* Collaborators: Zach Hornung, Klace Koch, and Timothy Viccari.
