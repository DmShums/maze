# maze

Example of the input file mazefile.txt:

5 5

4 1

3 4

*****

* * *

* *

* *  

  ***



An example of how the program works:

>>> maze = build_maze("mazefile.txt")

>>> print(maze)

* * * * * 

* _ * _ * 

* _ _ _ * 

* _ * _ _ 

_ _ * * * 

>>> maze.findPath()

True

>>> print(maze)

* * * * * 

* o * o * 

* x x x x * 

x * x * x x 

_ x * * * 

>>> maze.reset()

>>> print(maze)

* * * * * 

* _ * _ * 

* _ _ _ * 

* _ * _ _ 

_ _ * * *






