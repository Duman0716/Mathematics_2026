Exercise 12. Formula for a Matrix Power
Given:

A
=
(
1
1
0
1
)
1. Calculate 
A
2

A
2
=
(
1
1
0
1
)
(
1
1
0
1
)
A
2
=
(
1
2
0
1
)
2. Calculate 
A
3

A
3
=
A
2
A
A
3
=
(
1
3
0
1
)
3. Calculate 
A
4

A
4
=
A
3
A
A
4
=
(
1
4
0
1
)
4. Formulate a conjecture

From the calculations, we observe the following pattern:

A
n
=
(
1
n
0
1
)
for every nonnegative integer 
n
.

5. Prove the formula using mathematical induction

Assume that the formula is true for some nonnegative integer 
n
:

A
n
=
(
1
n
0
1
)
Multiply both sides by 
A
:

A
n
+
1
=
A
n
A
=
(
1
n
0
1
)
(
1
1
0
1
)
=
(
1
1
+
n
0
1
)
Therefore:

A
n
+
1
=
(
1
n
+
1
0
1
)
This is exactly the proposed formula with 
n
 replaced by 
n
+
1
.

Since the formula is true for 
n
=
0
, and the induction step holds, it is true for all nonnegative integers.
