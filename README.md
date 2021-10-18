# SnakesAndLadders

In this notebook you will find a Python coding solution to <a href="https://github.com/VoxelGroup/Katas.Code.SnakesAndLadders/" target="_blank">Voxel's Technical Interview kata - SnakesAndLadders</a> for the Sotfware Apprenticeship position.


### Main Goal & Requirements

The goal is to create a platform agnostic version of the classic game that can be used as backend. 
<br> Additionally, it needs to fulfill the following requirements:

* It has to be designed for **2 or more players** who will roll **a single 6 sided die**
* The outcome of the roll of the die will be **random**
* Snakes will take players downwards, ladders upwards
* The board will be a **10x10 grid** and players will **start at square 1**
* The players wil move their token across the board using the roll of a single die
* If the players land in square 97 they will need to roll a 3 in order to win. If they roll anything over 3 they will have to wait until they roll a 3 or lower.
* The first player to land in the **final square (nº 100) wins the game** and the bragging rights

### Structure of the notebook

I started creating a frontend version of the game since it is more interactive and easier to follow. <br>
Once I was satisfied with the results I went for a backend solution which was the main goal of the assignment.

Last but not least I included a "Room for growth" section with aspects that can be perfected.
