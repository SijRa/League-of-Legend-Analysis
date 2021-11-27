## The Analysis of High Elo Games in League of Legends
The code repository contains a Juypter Notebook file which aims to analyse a `.csv` file containing approximately 30,000 high elo games ranked matches.

## Motivation
In this Jupyter Notebook, we will try to explore a subset of factors in their effect of increasing the chance of winning your game. To achieve this, we will perform t-tests to compare the distributions between winning and losing factors to identify the most significant factors. Logestic regression will then be used to compare their effectiveness in predicting winning and losing games. 

## Project Overview

**Languages/Environments**
* Python 3.7
* Anaconda
* Jupyter Notebook

**Key Packages**
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

**Version Control**
* Git (GitDesktop)

**Install Anaconda Environment**
* conda env create -f environment.yml 
	* Installs packages to default conda environement (stats_lol) or specific environment with -p /home/user/anaconda3/envs/env_name

## League of Legends
League of Legends is an online MOBA game where two teams of 5 players (red and blue) compete to destory the opposing team's nexsus. Each player selects a 'champion' and fights the enemy champions for gold and experience points (exp) to buy better gear and become stronger.

## Glossary
* Warding totem: An item that gives vision.
* Minions: NPC that belong to both teams which give gold (and exp) when killed by players.
* Jungle minions: NPC that belong to no team. They also give gold (and exp) plus buffs when killed by players.
* Elite monsters: Monsters with high health/damage that give a massive bonus (gold/exp/stats) when killed by a team.
* Dragons: Elite monster which gives team bonus when killed. The 4th dragon killed by a team gives a massive stats bonus. The 5th dragon (Elder Dragon) offers a huge advantage to the team.
* Herald: Elite monster which gives stats bonus when killed by the player. It helps to push lanes and destroys structures.
* Towers: Structures you have to destroy to reach the enemy Nexus. They give gold.
* Level: Champion level. Start at 1. Max is 18.

## PHYS4038 Scientific Programming in Python (Machine Learning in Science)
__Sijan Shreesh Rana, *University of Nottingham*__
