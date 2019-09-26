### What is discrete maths, what is number theory?
* Discrete as in "chunks" - as opposed to Continuous mathematics
* Pertaining to whole numbers
* Number theory - where arithmetic meets discrete mathematics

### Applications of number theory:
* Cryptography - Primes, Divisibility
* Large integer calculations (modular arithmetic)
* Date and time calculations (modular arithmetic) 
	- Modular arithmetic is also known as "clock arithmetic"
* Solving optimization problems (integer linear programming)

### Notation for numbers:

* Natural numbers N =={0, 1, 2, ...}
* Integers Z = {..., -1, 0, 1, 2, ...}
* Positive integers N (>0) = Z (>0) = {1, 2, ...}
* Rational numbers (fractions) - expansion is finite, the ratio of two integers
* Real numbers (decimal or binary expansions) 

### Notation for Intervals:

[a,b] = {x : a <= x <= b} "[" and "]" are inclusive
(a,b) = {x : a < x < b} "(" and ")" are exclusive
so
[a,b) = {x : a <= x < b}
(a,b) = {x : a < x <= b}

(-inf,b] = {x: x <= b}
(-inf,b) = {x: x < b}
[a,inf) = {x: a <= x}
(a, inf) = {x: a < x}

so:

[-1,1] has 3 elements {-1, 0, 1}
(-1,1) has 1 element {0}

### Floor and Ceiling

* Floor(x) = greatest integer <= x
* ceiling(x) = the least integer >= x

Exercises:
2 * floor(0.6) - floor(1.2) = 2 * 0 - 1 = -1
2 * ceiling(0.6) - ceiling(1.2) = 2 - 2 = -1
ceiling((sqrt(3)) - floor(sqrt(3)) = 1
 - this is true for any non-integer

give x, y such that floor(x) + floor(y) < floor(x + y)
floor(-1.5) + floor(-1.5) < floor (-1.5 + -1.5)
= -2 + -2 < 0 = -2 < 0
