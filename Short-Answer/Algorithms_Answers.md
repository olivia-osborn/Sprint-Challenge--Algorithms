Add your answers to the Algorithms exercises here.
Exercise 1:
a) O(n)
b) O(n^3)
c) O(n)

Exercise 2:
The best way to test from what floor the eggs don't break when dropped is to test at story n/2. If the egg breaks, try halfway between that (1/4 n), and if the egg doesn't break, go up to halfway between that and the top (3/4 n). Keep splitting the floors in half until you find the floor at which the eggs do not break, and this will save much more time than testing each floor one at a time. The runtime complexity will equal O(nlog(n)).
