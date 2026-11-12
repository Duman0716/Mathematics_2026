Exercise 3. When Can Matrices Be Multiplied?
Given:

A
2
×
3
,
B
3
×
4
,
C
4
×
2
,
D
2
×
2
Multiplication rule:

If matrix 
X
 has size 
m
×
n
 and matrix 
Y
 has size 
p
×
q
, then 
X
Y
 is defined only if:

n
=
p
The resulting matrix has size:

m
×
q
1. 
A
B

(
2
×
3
)
(
3
×
4
)
The inner dimensions match.

A
B
:
 
2
×
4
2. 
B
A

(
3
×
4
)
(
2
×
3
)
The inner dimensions 
4
 and 
2
 do not match.

B
A
:
 Not defined
3. 
B
C

(
3
×
4
)
(
4
×
2
)
The inner dimensions match.

B
C
:
 
3
×
2
4. 
C
B

(
4
×
2
)
(
3
×
4
)
The inner dimensions 
2
 and 
3
 do not match.

C
B
:
 Not defined
5. 
A
C

(
2
×
3
)
(
4
×
2
)
The inner dimensions 
3
 and 
4
 do not match.

A
C
:
 Not defined
6. 
C
A

(
4
×
2
)
(
2
×
3
)
The inner dimensions match.

C
A
:
 
4
×
3
7. 
A
D

(
2
×
3
)
(
2
×
2
)
The inner dimensions 
3
 and 
2
 do not match.

A
D
:
 Not defined
8. 
D
A

(
2
×
2
)
(
2
×
3
)
The inner dimensions match.

D
A
:
 
2
×
3
Summary:


Product	Defined?	Result size
A
B
Yes	
2
×
4
B
A
No	-
B
C
Yes	
3
×
2
C
B
No	-
A
C
No	-
C
A
Yes	
4
×
3
A
D
No	-
D
A
Yes	
2
×
3
Explanation: Matrix multiplication depends on the compatibility of the inner dimensions. The number of columns of the first matrix must equal the number of rows of the second matrix.

