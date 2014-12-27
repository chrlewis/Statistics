Statistics
==========
This is a repository for holding programs written in Java to explore the use of Bayes Theorem.
The first program relates to the Monty Hall problem http://en.wikipedia.org/wiki/Monty_Hall_problem
which can be summaried as follows. 
Suppose you're on a game show, and you're given the choice of three doors: Behind one door is a car; 
behind the others, goats. You pick a door, say No. 1, and the host, who knows what's behind the doors, 
opens another door, say No. 3, which has a goat. He then says to you, "Do you want to pick door No. 2?" 
Is it to your advantage to switch your choice?
Most people think there is no advantage, however Bayes Theorem predicts otherwise.
The first program, zipped as Bayes.zip has four classes. The first selects a door at random behind
which the prize is located. The second picks a door at random to represent the contestant's first
guess. The third, iterates through a loop 1,000,000 times. During each iteration, random prize
doors and initial guesses are selected. The loop then considers all possibilities for which door
Monty opens and assumes the contestant changes the initial door selection, in line with Bayes
recommendation. The final class is a driver class to execute code. 
The resulting number of correct guesses is then calculated and displayed. This empirical
proof shows Bayes theorem recommendations yield a correct guess in line with the predicted 2/3 chance.
