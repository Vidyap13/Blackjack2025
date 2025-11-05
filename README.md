# Blackjack2025
Reinforcement Learning - BlackJack Player
---------------------------------
This repository contains a Jupyter Notebook (TaskP3_1.ipynb) that implements and compares various Reinforcement Learning (RL) methods for Blackjack strategy evaluation, focusing on win rates, average profit, and ROI under different game rule scenarios.

##Overview
This project explores the learning and evaluation of basic and advanced Blackjack strategies using RL algorithms, specifically Expected SARSA and Monte Carlo methods. It focuses on how different game rules ("Basic strategy", "CPC", "Resplit of Aces", "Dealer hole card", etc.) and learning approaches impact win rate and profitability for the player.
The notebook trains RL agents for each scenario and displays performance metrics such as win/loss/draw rates, average profit per game, and ROI.

Implemented Algorithms
•	Expected SARSA: On-policy Temporal Difference RL algorithm estimating expected value for next state/action.
•	Monte Carlo: Model-free method learning from episodic experience and averaging returns.
•	EnhancedExpectedSARSA: Improved version of Expected SARSA, used with enhanced strategies/scenarios.

Evaluated Scenarios
The following game rules and strategy variants are investigated:
1.	Basic Strategy (ExpectedSARSA / MonteCarlo)
2.	CPC Strategy (ExpectedSARSA / MonteCarlo)
3.	Enhanced CPC Strategy (EnhancedExpectedSARSA)
4.	Resplit of Aces (ExpectedSARSA / MonteCarlo)
5.	Dealer Hole Card Rule (ExpectedSARSA / MonteCarlo)
Each scenario/algorithm pair is trained for a large number of episodes (typically hundreds of thousands or more).

##Requirements
•	Python 3.7+
•	Jupyter Notebook / JupyterLab
•	numpy
•	matplotlib
•	(Optionally) tqdm for progress bars

##How to Run
1.	Clone or download this repository.
2.	Open TaskP3_1.ipynb in Jupyter Notebook or JupyterLab.
3.	Run each cell from top to bottom. The notebook will:
	o	Train RL agents for each scenario/algorithm.
	o	Display win/loss/draw stats and other performance summaries.
	o	Produce training result plots.
Note: Training takes several minutes per scenario.

##Visualization
The notebook includes Matplotlib visualizations comparing win rates and ROI across different RL algorithms and scenarios

## Authors
Vidya Padmanabha (k70818)
