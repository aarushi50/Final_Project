# BINGO - An application of Monte Carlo Simulation

## Team Member(s):
Aarushi Mishra

# Monte Carlo Simulation Scenario & Purpose:

A Bingo Club is planning to introduce two new windfalls to attract more participants. Windfall gain is any type of unusually high or abundant income that is sudden and/or unexpected.The profit perspective lies in the fact that it is highly uncertain whether a person will win the game choosing to play with special tickets for windfalls that cost higher than the usual tickets.

The aim of the this simulation is to inform the decision of the club on what pay-out amount should be designated for each windfall gain.

## Simulation's variables of uncertainty

The whole environment of the game can be divided into two parts. The varibales of uncertainty for those two parts are:

1. For ticket/card generation:

  a. Numbers printed on the ticket -> Uniform <br />
  b. Position of numbers on the ticket->  Uniform <br />
  c. Lucky number for lucky star ticket -> Uniform <br />

2. For Game:

  a. Number of players -> Discrete Random <br />
  b. The number called out by the caller -> Uniform <br />



## Hypothesis or hypotheses before running the simulation:

#### "The pay-out amount for each windfall must be double the price of the ticket." 

## Analytical Summary of your findings: (e.g. Did you adjust the scenario based on previous simulation outcomes?  What are the management decisions one could make from your simulation's output, etc.)

## Instructions on how to use the program:

As of 04/25 : <br />

ticket_genertor.py creates and displays the type of ticket specified. <br />
The ticket generated goes strictly with the design of an actual ticket. Each generated ticket has 3 rows, 9 columns, 15 non duplicate numbers, 5 numbers in each row, 4 spaces in each row.<br />
To see a sample ticket, simply run the program.<br />
<br />
bingo_game.py allows to find the winners for usual 4 winning combinations (not windfalls yet). Presently, a hard coded ticket is used to test the functionality of the class.<br />
To see how the game goes, simply run the file.<br />


## All Sources Used:

For exploring the topic and related factors:

  https://en.wikipedia.org/wiki/Bingo_(United_Kingdom) <br />
  https://en.wikipedia.org/wiki/Bingo_(U.S.) <br />
  http://bingonut.net/windfall-gain-bingo.html <br />
  http://www.freebingoticket.com/tickets/10407 <br />
  https://www.statista.com/statistics/203432/bingo-gross-gaming-sales-in-the-uk/ <br />

For coding:

https://docs.python.org/3/ <br />
https://www.python.org/doc/ <br />
http://docs.python-guide.org/en/latest/writing/documentation/  <br />
"Programming in Python 3", 2nd Edition, by Mark Summerfield, ©2010

