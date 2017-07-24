# OCR_Game_client-server

This is a multithread (2 player) OCR game (application to recognize words in images). In this application there is a list of unknown words, and each word is presented to both users and it is asked to them to input what they see. If their inputs match, it is assumed that they input the correct value of the word.

# GAMEPLAY:
- The goal of the game is to move the character from the initial position to the ending position.
- By inserting the correct words, the users will make the character to move closer to the goal.

# NOTES:
- This application has multiple threads (One main one that controls the gameplay; one that performs the running animation of the character and the spinning animation of the goal and a third one that performs the winning animation sequence).

# HOW TO RUN IT:
1. Start the server (ServerGUI.java).
2. Start two instances of the client (HumanOCRGame.java).