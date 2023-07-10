# Game-Card
My Card Game includes 3 cards per person and you can choose how many rounds you want.

----- Rule for 1 round    
    Rule 1: There may have many people win.
         - If any hands have 3 cards from Jack to King, this hand will win.
    
    Rule 2 (if rule 1 have no result):There may have many people win.
         - The sum of total of 3 cards (Jack, Queen and King are equal 10 points, and Ace is equal 1 point).
         _ Compare the unit number of the sum, the highest number is win.
         _ If there is more than 1 person Win, we consider the first number of the sum, the highest number is Win.
    
    Example 1:      Player 1 has 3 cards: King of Clubs, King of Spades and Jack of Spades.
                    Player 2 has 3 cards: Queen of Clubs, Queen of Spades and 10 of Diamond.
                    Player 3 has 3 cards: Ace of Hearts, 2 of Spades and 6 of Spades. 
                
                ==> Player 1 Win
    
    Example 2:      Player 1 has 3 cards: 7 of Clubs, 9 of Spades and 3 of Spades.
                    Player 2 has 3 cards: 8 of Clubs, King of Spades and Ace of Diamond.
                    Player 3 has 3 cards: Ace of Hearts, 2 of Spades and 6 of Spades.
                 
                The sum of Player 1 is 19, so the numbers of Player 1 are 1 and 9.
                The sum of Player 2 is 19, so the numbers of Player 2 are 1 and 9.
                The sum of Player 3 is 9, so the numbers of Player 3 are 0 and 9.
                
                ==> Player 1 Win and Player 2 Win.
    
    Example 3:      Player 1 has 3 cards: King of Clubs, 9 of Spades and Jack of Spades.
                    Player 2 has 3 cards: 8 of Clubs, King of Spades and Ace of Diamond.
                    Player 3 has 3 cards: Ace of Hearts, 2 of Spades and 6 of Spades.
                 
                The sum of Player 1 is 29, so the numbers of Player 1 are 2 and 9.
                The sum of Player 2 is 19, so the numbers of Player 2 are 1 and 9.
                The sum of Player 3 is 9, so the numbers of Player 3 are 0 and 9.
                
                ==> Player 1 Win. 
                
-----Expand: (Playing many rounds) There may have many people win.
Through each round, players who win will get 1 point. After all rounds, players who have highest point will win
