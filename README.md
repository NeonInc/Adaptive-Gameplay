# Evolving Enemies
## Using a Genetic Algorithm to control Enemy behavior in Video Games

This code uses the concepts of Genetic Algorithms such as Selection, Crossover and Mutation to control and evolve Enemy behavior. 

The enire behavior of the enemy is coded in the structure of a chromosome.

<p align="center">
  <img width="650" height="300" src="https://github.com/NeonInc/Adaptive-Gameplay/blob/master/Images/Chromosome_Attributes.png">
</p>

Genes 0 - 5 are in binary format with 0 being the respective option disabled and 1 being being the respective option enabled.
Gene 6 is in decimal format to record the fitness value of the chromosome.

### Dependencies (pip install)
```
pygame
pygame-menu
```
### Usage

```
python3 evolving_enemies.py
```
#### Main Menu

The Main Menu allows the players to navigate to Play Menu and the Help and About Menus. The Help Menu details the game controls while About Menu lists game information.

<p align="center">
  <img width="640" height="480" src="https://github.com/NeonInc/Adaptive-Gameplay/blob/master/Images/Main_Menu.png">
</p>

#### Play Menu
<p align="center">
  <img width="640" height="480" src="https://github.com/NeonInc/Adaptive-Gameplay/blob/master/Images/Play_Menu.png">
</p>
