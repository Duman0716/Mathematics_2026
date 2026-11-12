Exercise 11. When Do Matrices Commute?
Given:

A
=
(
1
1
0
1
)
,
B
=
(
a
b
c
d
)
We want to find the conditions under which:

A
B
=
B
A
1. Calculate 
A
B

A
B
=
(
1
1
0
1
)
(
a
b
c
d
)
A
B
=
(
a
+
c
b
+
d
c
d
)
2. Calculate 
B
A

B
A
=
(
a
b
c
d
)
(
1
1
0
1
)
B
A
=
(
a
a
+
b
c
c
+
d
)
3. Set the matrices equal

(
a
+
c
b
+
d
c
d
)
=
(
a
a
+
b
c
c
+
d
)
Comparing corresponding entries gives:

a
+
c
=
a
b
+
d
=
a
+
b
c
=
c
d
=
c
+
d
From the first equation:

c
=
0
From the second equation:

d
=
a
The fourth equation also gives 
c
=
0
, so there are no additional conditions.

Final result:

B
=
(
a
b
0
a
)
where 
a
 and 
b
 are arbitrary real numbers.

Explanation: Although matrix multiplication is generally noncommutative, certain matrices commute. In this example, all matrices of the displayed form commute with 
A
.

Verification:

Substituting 
c
=
0
 and 
d
=
a
:

A
B
=
(
a
b
+
a
0
a
)
B
A
=
(
a
a
+
b
0
a
)
Both matrices are equal.
