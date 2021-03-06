## INFO6205_PSA_FinalProject
## Team Members

- Shenckerr Gollapudi - 001569753
- Ganesh Kumar Dharani - 002191922
- Nithin Sai Guvvala - 001521107

## INFO6205 Final Project : The Menace
- Prof. Robin Hillyard

- We developed two modules as a part of this project ( *DEMO VIDEOS AVAILABLE IN THE REPOSITORY* )

- 1. Training (Training_FinalProject_Menace) : To train the menace against human strategy UI that shows the progress of the training as a part of requirement
- 2. Game (PlayerVsMenace): Program that enables a player to play against the menace that is trained using the above program

# Steps to run the project

- 1. We have implemented the UIs using PySimpleGUI

- 2. To install the dependencies run the below command in the terminal and further the projects are ready to run

```
pip install PySimpleGUI
```

- 3. To run the training (demo video available)
	- Run 'unitTestMenace.py' to run the unit tests
	- Run 'startTraining.py' to start training the menace 
	- UI window opens and click on 'Start Training' button to start viewing traing process
	- 'BewareOfMatchBoxes.py' file has the source code for training


- 4. To play the game (*Please wait for around 30 sec* for the menace to get trained) (demo video available)
	- Run the 'gameVsMenace.py' file. 
	- UI window pops up 'Please wait (Click OK on the popup to start the training). 
	- Wait(*Around 30sec* to get trained) for the menace to get trained 
	- Once the training is done, another popup occurs that training is done. 
	- Click ok. And the game window opens and The Menace is ready to play.
	- Select the game mode(Menace first/ Player First) and start playing

# Project Output
![alt text](Game.gif)

