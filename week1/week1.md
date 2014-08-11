
Week 1 Notes
=============

These are the notes for week 1 of Math 3001.

Introduction to Scientific Computing
-------------

Scientific Computing is
* Using the computer to aid you in solving problems. 
* Often you'll write programs (algorithms and code) to solve the problems. 
* Requires math or science knowledge to be effective.


Scientific Computing is not
* just writing code
* a substitute for math or science
* a magic bullet to solve any problem


Numeric Types
-------------

One of the first things that is important is a knowledge of how computers store numbers and other mathematical objects.  The following are links to wikipedia pages with further information:

* [wikipedia's page on integers](http://en.wikipedia.org/wiki/Integer_(computer_science\))
* [wikipedia's page on floating point numbers](http://en.wikipedia.org/wiki/Floating_point_numbers)


Julia's standard numbers and mathmatical objects
----------------

Julia has built-in number and other mathematical data types including those listed above in various sizes as well as rational numbers, matrices, and complex numbers.  The following is a 

* [julia doc for integers](http://docs.julialang.org/en/latest/manual/integers-and-floating-point-numbers/)
* [julia doc for floating point](http://docs.julialang.org/en/latest/manual/integers-and-floating-point-numbers/)
* [julia doc for rational numbers](http://docs.julialang.org/en/latest/manual/complex-and-rational-numbers/)
* [julia doc for complex numbers](http://docs.julialang.org/en/latest/manual/complex-and-rational-numbers/)
* [julila doc for arrays](http://docs.julialang.org/en/latest/manual/arrays/)


Rounding Errors and the Quadratic Formula
------------

The following example shows how a well-know formula (the quadratic formula) can lead to incorrect results due to rounding errors.  

Remember if you solve \\(a{x}^{2}+bx+c=0\\), the the quadratic formula finds the solution:

\\[d\\]

\\[ x=\frac{-b \pm \sqrt{{b}^{2}-4ac}} {2a}\\]

Use the quadratic formula to solve \\({x}^{2}-x-110=0\\).

Next, let's consider the quadratic equation \\(12.242{x}^{2}+42.382x+36.671=0\\)

In julia define the constants a, b, and c as the coefficients and then use the quadratic formula to find the two solutions.   What do you get?

Next, redefine a, b and c, however use the float16 (16-bit floating point) versions of the 3 coefficients and find the two solutions.  What do you get?  What happened?


Be skeptical of numerical answers
--------------

Even though the example above was manufactured to produce bad results, you never know if a numerical solution is accurate or not.  

