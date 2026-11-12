Exercise 13. A Recurrence Written in Matrix Form
Given:

F
=
(
1
1
1
0
)
1. Calculate 
F
2

F
2
=
(
1
1
1
0
)
(
1
1
1
0
)
F
2
=
(
2
1
1
1
)
2. Calculate 
F
3

F
3
=
F
2
F
F
3
=
(
3
2
2
1
)
3. Calculate 
F
4

F
4
=
F
3
F
F
4
=
(
5
3
3
2
)
4. Calculate 
F
5

F
5
=
F
4
F
F
5
=
(
8
5
5
3
)
5. Relationship with the Fibonacci sequence

The Fibonacci sequence is:

0
,
1
,
1
,
2
,
3
,
5
,
8
,
13
,
…
Each term is the sum of the two preceding terms:

F
n
=
F
n
−
1
+
F
n
−
2
The matrix powers contain consecutive Fibonacci numbers:

F
n
=
(
F
n
+
1
F
n
F
n
F
n
−
1
)
for 
n
≥
1
, where 
F
0
=
0
 and 
F
1
=
1
.

6. Matrix-vector multiplication

Consider:

F
(
a
b
)
=
(
1
1
1
0
)
(
a
b
)
=
(
a
+
b
a
)
Explanation: The new vector contains the sum of the two previous values in its first position and keeps the previous first value in its second position.

This performs one step of the Fibonacci recurrence.
