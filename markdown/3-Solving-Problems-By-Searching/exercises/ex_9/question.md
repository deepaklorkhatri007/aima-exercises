[Exercise 3.9 \[path-planning-exercise\]](ex_9/)

Consider the problem of finding the shortest
path between two points on a plane that has convex polygonal obstacles
as shown in Figure [polygonal obstacles](#polygonal-obstacles). This is an idealization of the problem that a robot has to
solve to navigate in a crowded environment.

1.  Suppose the state space consists of all positions $(x,y)$ in
    the plane. How many states are there? How many paths are there to
    the goal?

2.  Explain briefly why the shortest path from one polygon vertex to any
    other in the scene must consist of straight-line segments joining
    some of the vertices of the polygons. Define a good state space now.
    How large is this state space?

3.  Define the necessary functions to implement the search problem,
    including an function that takes a vertex as input and returns a set
    of vectors, each of which maps the current vertex to one of the
    vertices that can be reached in a straight line. (Do not forget the
    neighbors on the same polygon.) Use the straight-line distance for
    the heuristic function.

4.  Apply one or more of the algorithms in this chapter to solve a range
    of problems in the domain, and comment on their performance.
<br>
<b id='polygonal-obstacles'>Figure</b> A scene with polygonal obstacles. S and G are the start and goal states.
![polygonal obstacles](http://nalinc.github.io/aima-exercises/Jupyter%20notebook/figures/geometric-scene.svg)