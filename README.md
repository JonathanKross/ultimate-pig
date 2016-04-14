# Ultimate Pig
This project analyzes the game of pig solitaire, a single-player dice game. A player has 7 turns in which to score the most number of points possible.

### Game Rules
* If the player rolls a 1, all points are lost and the turn is over
* The player must roll at least once, but may roll as many times as they wish within a single turn
* Each turn's score is the sum of their rolls (except if they roll a 1, in which case that turn is worth a total of 0 points)
* The player may choose to hold their current turn score at any time after a non-1 die roll

## Objective
Find the best strategy for this game, the "ultimate pig" player.


## To View This Notebook
Just click the `ultimate-pig.ipynb` file above.

## To Run This Notebook
#### System Requirements / Installation

* You will need to have **python3** installed

* Clone this repo onto your machine.

* You will need to make sure that you have a virtual environment running in the working directory

* In your command-line program, install the requirements file by runnning **`pip install -r requirements.txt`**.

#### Opening the Notebook
* From your working directory, using the command-line prompt: **`ipython notebook ultimate-pig.ipynb`**
