# Optimal_Execution_Almgren_and_Chriss_Model
Almgren and Chriss Model For Optimal Execution of Portfolio Transactions

<br>
<br>

## Almgren and Chriss Model

<br>
<br>

## Trading Lists

<br>
<br>

## Efficient Frontier

<br>
<br>

## Deep Reinforcement Learning

Apply basic DRL framework for ddpg in our model
<br>
<br>

## TODO

Here are a few things will try out:

- Incorporate your own reward function in the simulation environmet to see if you can achieve a expected shortfall that is better (lower) than that produced by the Almgren and Chriss model.


- Experiment rewarding the agent at every step and only giving a reward at the end.


- Use more realistic price dynamics, such as geometric brownian motion (GBM). The equations used to model GBM can be found in section 3b of this [paper](https://ro.uow.edu.au/cgi/viewcontent.cgi?referer=https://www.google.com/&httpsredir=1&article=1705&context=aabfj)


- Try different functions for the action. You can change the values of the actions produced by the agent by using different functions. You can choose your function depending on the interpretation you give to the action. For example, you could set the action to be a function of the trading rate.


- Add more complex dynamics to the environment. Try incorporate trading fees, for example. This can be done by adding and extra term to the fixed cost of selling, $\epsilon$.