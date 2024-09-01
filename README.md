# Grungle Card / Dice Game

Work in Progress

---

Grungle is an experimental proof of concept card/dice game. The objective of the game is to remove pairs of cards from the board by matching up their suit and numerical value. The game starts by picking up cards from a randomly shuffled deck of 8 suits. Each card in each suit has been given a numerical value 1 through 6. The player takes each turn places cards on the board and using the randomly rolled dice result to change the value of any card they want. When they match the cards suits with the same value, the cards are removed from the board and the dice is rolled again. When all the pairs have been removed, the player wins and the game is complete.

Currently functioning proof of concept. Without rerolls game provides serious challenge if not heavy on rng. x3 re-rolls might suffice to keep the joy of the challenge but also make it just that bit easier so as to be more fun and less tedious probability.

Another point to consider is seeing how the game feels with only 7 suits. 8 suits on a 9 square board means that if your unlucky and get all 8 suits on the board, you have 1 square left to get the singular matching suit card and then you are behest of lady luck on the dice rolls. or a 5/9 chance.

Need to add win condition with a celebration animation. matrix rainfall of coins maybe?

Bug Report: Card duplication happening only slightly (it can be avoided with careful placement of cards) which leads me to believe that it is happening when the card is returned to deck because of not being placed or trying to place during dice roll/animation. Need to make sure that my logic is handling the deck arrays correctly and if not, write up tests to see exactly what is happening.
