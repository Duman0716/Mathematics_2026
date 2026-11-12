Exercise 8. Row Operations and Their Reversibility
Given:

A
=
(
1
2
−
1
2
4
1
−
1
1
3
)
Step 1: 
R
2
←
R
2
−
2
R
1

R
2
=
(
2
,
4
,
1
)
−
2
(
1
,
2
,
−
1
)
R
2
=
(
0
,
0
,
3
)
The resulting matrix is:

(
1
2
−
1
0
0
3
−
1
1
3
)
Reverse operation:

R
2
←
R
2
+
2
R
1
Step 2: 
R
3
←
R
3
+
R
1

R
3
=
(
−
1
,
1
,
3
)
+
(
1
,
2
,
−
1
)
R
3
=
(
0
,
3
,
2
)
The resulting matrix is:

(
1
2
−
1
0
0
3
0
3
2
)
Reverse operation:

R
3
←
R
3
−
R
1
Step 3: Interchange 
R
2
 and 
R
3

The resulting matrix is:

(
1
2
−
1
0
3
2
0
0
3
)
Reverse operation:

Interchange 
R
2
 and 
R
3
 again.

Explanation: Elementary row operations are reversible. The three types of operations are:

Swapping two rows.
Multiplying a row by a nonzero scalar.
Adding a multiple of one row to another row.
Each operation has an inverse that restores the original matrix.
