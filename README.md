# A-star-is-born
## A demonstration using the A* algorithm
#### According to "Algorithms in a Nutshell," an A* algorithm "is an iterative ordered search that maintains a set of open board states to explore in an attempt to reach the goal state."

#### Defined by the function f(n) = g(n) + h(n) where g(n) records the length of the shortest sequence of moves from the initial state n while h(n) estimates the length of the shortest sequence of moves from n to the goal state.

#### There are a number of limitations to the provided code, notably h(n) is a rough estimation basted on the distance from the current node to the end 'as a crow flies.' Diagonal moves are also considered the same as horizontal moves. 

#### The demonstration provided in file "sketch.js" was inspired by the youtube channel "The Code Train." A solution is not always possible. If that is the case then "no solution" is logged to the browser console. 

## Technologies Used: 
### Javascript
### p5.js
### html

