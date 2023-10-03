# ANN_for_rosenbrock_optimisation
In this project,we use ANN to test and train optimisation function  by generating non linear dataset/
In applied mathematics, test functions, known as artificial landscapes, are useful to evaluate characteristics of optimization algorithms, such as:
Convergence rate.
Precision.
Robustness.
General performance.

One such function is the rosenbrock function.
 The Rosenbrock function is a non-convex function, introduced by Howard H. Rosenbrock in 1960, which is used as a performance test problem for optimization algorithms.[1] It is also known as Rosenbrock's valley or Rosenbrock's banana function.
The global minimum is inside a long, narrow, parabolic shaped flat valley. To find the valley is trivial. To converge to the global minimum, however, is difficult.The function is defined by:
** f(x,y)=(a-x)^{2}+b(y-x^{2})^{2}**
It has a global minimum at (x,y)=(a,a^{2}), where f(x,y)=0. Usually, these parameters are set such that a=1 and b=100. Only in the trivial case where a=0 the function is symmetric and the minimum is at the origin.

We use this function to generate a non linear dataset and use this data to create a ANN and perform analysis by variation of different parameters,while comparing the variation and their results.
