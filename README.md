# Ant-Colony-Optimisation
Ant colony optimization is a technique that is used for solving computationally intensive problems which can be reduced to the path finding problem. 
It gives an approximate solution to the targeted problem, but this approach is faster. 
In this, we model the real behavior of ants which leave the pheromone on the path they travel. 
Most used path has the stronger pheromone. Multiple ants are placed that makes best choices at a time. 
Simulation results in this choice is one of the best. It does guarantee the optimal solution, however. 
Travelling salesman problem and internet routing are the few example that can be solved by it. 
Technique is parallel in nature because we can simultaneously simulate the behavior of multiple ants then we can accumulate the results. 
We will solve the salesman problem using the same.
Software Requirements so as to run the code on your system are:
1)	C++ GCC 10.0V compiler in Ubuntu (Terminal) or Windows (Code Blocks)
2)	Performance Profilers being used are gprof and valgrind.
Various tools allow the profiling of a program on the Unix environment. 
Gprof and valgrind are two of those. With gprof we can find the parts of programs that take more running time. 
In this way, we can optimize certain parts of the program that results in good performance gains. 
Valgrind is also the tool for profiling, memory leaks detection, and debugging of a program on the Linux environment. 
We can use these while using the gcc compiler.

