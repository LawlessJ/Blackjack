					
				--------BLACKJACK-------

Required: Python 3.7 (Free download here: https://www.python.org/downloads/)
Code can be executed in terminal. After downloading the blackjack.py file, navigate the terminal to your working directory and enter command:
>>python3 blackjack.py
to execute the code and play the game.


This program simulates the game of blackjack, a casino style card game (rules here: https://www.blackjackapprenticeship.com/how-to-play-blackjack/)

As of now, this is a one-on-one play vs the dealer (future update may allow for extra players).

There is not currently a "split" option, but this may also become available in later updates. I also did not include a "surrender" option, but that's because I have never played those rules in blackjack.

In execution of the game, the player is started out with $200 in chips, and a default bet of $25. The option to alter this bet can be done, up to a maximum of the total chips a player has. Cards are then randomly dealt to the player and to the dealer. If neither has an immediate 21 in the deal, the player is given the option to hit (draw a new card), stand (pass play to the dealer) or double down (double current bet, draw a new card and pass play to the dealer).

The dealer's play is automated, though their actions are displayed on screen. They will always hit until their score is at least 17, then stand. 

At the end of each hand, the option to deal again or cash out is offered. Cashing out will end the program and display the winnings (or losses) to the player.
