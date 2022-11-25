## Homework: life

The goal is to find a still (stable) live organism within $N\times N$ subsquare of an (infinite) board of Conway's game of life. The organism must not change in time, the goal is to maximize its density (the number of live cells divided by $N^2$). 

See the problem description on [CSPLib.org](https://www.csplib.org/Problems/prob032/). (But don't look at the solutions there. Also, in 2012 the problem was solved mathematically, but don't use the formula.)

Try to improve your model using symmetry breaking, implicit constraints, perhaps a good search strategy, etc.

```
picat life.pi 8
```
should return the optimal value of `36` and some representation of the organism.

