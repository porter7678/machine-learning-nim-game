# machine-learning-nim-game
Machine learning algorithm allowing a computer to teach itself the winning strategy for the simple strategy game of Nim and defeat any human opponent.

Note: I did not pre-program the computer with the winning strategy. In fact, until this program was finished, I didn't even know the winning strategy myself. Rather, I programmed the computer to play thousands of games against itself, each time giving every move a score based on how effective that move was until the computer taught itself the winning strategy.

# Rules of Nim
Nim is a simple mathematical strategy game.

In this variant, there are three piles of stones consisting of 7, 5, and 3 stones respectively.

Each player takes a turn removing as many stones as they desire from exactly one of the piles.

For example, I could choose to take 4 stones from pile 2 leaving a game board of {7, 1, 3}

Players cannot remove a stone from an empty pile.

A player must remove at least one stone on their turn.

A player cannot remove stones from multiple piles in a single turn.

The winner is the player who removes the last stone from the last pile, reducing the board to three empty piles


It is important to note that Nim is a completely solved game. Therefore, if the player who goes first plays a perfect game, it is impossible for the second player to win.

# A Challenge
I challenge you to play against the program I have built (going first or second) and see how many games it takes you before you figure out the winning strategy such that you can always beat the computer if you go first!
