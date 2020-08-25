# Option_prediction_in_a_card_game

The program is designed to give a prediction for the best option for a particular player in a traditional game of four cards. It uses basic user profiling and past moves to predict the best move for any particular player in the game.

The game consists of 16 cards of 4 types with 4 cards each and is played between 4 players. The prediction is done using a weightage system that assigns a probability value to all the four options of the cards that a user can pass to the adjacent user on the next turn.

The weights for all the four cards are calculated based on the previous cards exchanged to the player. Each user carries four cards at a particular time and has to pass a single card to the player right to him. If a person gets all the four cards of the same type, then he/she wins the game. After this, the profile label of the player who passed the card and the data of the player who will receive the card is used to calculate the best possible move for the required player.
