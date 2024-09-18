# Cardbungle Card / Dice Game

Work in Progress

---

Cardbungle is an experimental proof of concept card/dice game. The objective of the game is to remove pairs of cards from the board by matching up their suit and numerical value. The game starts by picking up cards from a randomly shuffled deck of 8 suits. Each card in each suit has been given a numerical value 1 through 6. The player takes each turn places cards on the board and using the randomly rolled dice result to change the value of any card they want. When they match the cards suits with the same value, the cards are removed from the board and the dice is rolled again. When all the pairs have been removed, the player wins and the game is complete.

Currently functioning proof of concept. Without rerolls game provides serious challenge if not heavy on rng. x3 re-rolls might suffice to keep the joy of the challenge but also make it just that bit easier so as to be more fun and less tedious probability.

Need to add a more visually appealing win condition with a celebration animation. matrix rainfall of coins maybe? Currently just set to an alert.

Bugs Report: Card duplication happening on occassion. I believe it has something to do with when the card is not placed correctly and attempts to return to the deck, but instead duplicates. After watching someone play the game and getting some feedback I think it might be better to have controls that when you select the card instead of having to hold the mouse click down, it anchors the card to the cursor and then click again to drop. Same for the dice.
