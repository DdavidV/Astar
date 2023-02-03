# Astar
<h2>Requirements</h2>

-Python 3.8+<br>
-Pygame

pip install pygame --pre

<h2>How to use it</h2>

-1st and 2nd click places the start and the end node.<br>
-Every click after the first 2: place a barrier node that should be avoided by the algorythm.<br>
-Use right click to delete a node.<br>
-Use 'c' to clear everything.<br>
-Use space to start.<br>

<h2>How does it work?</h2>

A* is a popular search algorithm used for finding the shortest path between two points, or for finding the solution to a problem by searching through a graph. It works by combining the information from a heuristic function and a cost function to estimate the minimum cost from the starting point to the goal. A* keeps track of the best path it has seen so far and updates the estimate cost for each node it visits until it reaches the goal. The algorithm prioritizes visiting nodes that are likely to lead to the goal first, making it an efficient and effective search strategy.

f(n)=g(n)+h(n)
