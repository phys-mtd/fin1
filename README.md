#Final Part 1

##Polygon Geometry -- Calculation of Pi

This code will approximate pi by calculating the perimeter of n-gons for large values of n. This code is a fixed version of the code provided by Dr. Michael Rozman for Physics 2200 at the University of Connecticut. The first code uses a formula that was provided in class for finding the half-angle sin from a given value of sin. It output calculations that would give large error for values of n > 2^15. This error was found to occur since the equations end up becoming 1 minus at small numbers for large n. This code now fixes the error within the previous code and gives the correct output as well as giving a correctly linearized plot.
