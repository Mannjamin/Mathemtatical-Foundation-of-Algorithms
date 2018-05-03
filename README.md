# The Mathematical Foundations of Algorithms

## Table of Contents:

 - Variables
 - Sets
 - Equations
 - Functions
 - Subscripts
 - Summation
 - Products
	 - And more!

## Variables:
A variable is a symbol used to represent a mathematical construct
> Numbers, sets, lists , vectors, matrices, …

Often lower case letters or Greek letters are used
> *x, y, z,* Ω, *α*, β, …

Variables in Mathematics are treated the same as variables within a programming language. They can be thought of as a box containing a value that can be read from or written to.

## Sets:

 - A set is a finite or infinite collection of items.
 - A set has no order.
 - You cannot index a set… 
 - A set only contains one copy of an item.

Symbol | Name | Meaning / Definition
:--------: | :-----: |:--------:
a ∈ A | Element of |Item is a member of set A.
a ∉ A | Not Element of |Item is not a member of set A.
Ø | Empty Set |Represents an Empty Set.
*/A/*|Cardinality|The number of elements of set A.
***R***|Real Numbers|A set of Real Numbers.
***Z***|Integers| A set of Integers.
***N***|Natural Numbers| A set of Natural Numbers.

> The entire alphabet can be used to define a set.
>[You can find more Mathematical Symbol Meanings here](https://www.rapidtables.com/math/symbols/Basic_Math_Symbols.html).

### Set Operators:

#### Creating A Set:

The process of defining a set:
 1. A = {variable : inclusion criteria}.
 2. A = {n^2^ : n is an integer and 0 ≤ n ≤ 5}.
 3. A = {0, 1, 4, 9, 16, 25}.

#### Unifying a set:

The process of unifying a set:
 1. A = B ∪ C.
 2. A = *{a : a ∪ B **OR** a ∈ C}*.
 3. A contains all of B and C.

 #### Intersection of a set:
 
 The process of Intersection:
 1. A = B  ∩  C
 2. A = *{a : a ∈ B **AND** a ∈ C}*
 3. A contains only what B and C have in common

#### Subsets and Superset:
##### If A is a Set:
Symbol | Name | Meaning / Definition
:--------: | :-----: |:--------:
B ⊆ A | Subset |B ⊆ A means B is a Subset of A **AND** Set B is included in Set A.
B ⊂ A|Proper/Strict Subset|B is a subset of A, but B is not equal to A.
B ⊇ A|Superset|B is a Superset of A. Set-B includes Set-A.
A ⊅ B|Not a Superset|Set-B is not a superset of Set-A

#### Subtraction:

The process of Subtraction:
 1. A = C\B.
 2. A = *{a : a ∈ C **AND** a ∉ B}.*
 3. A is B with all the elements of C removed

## Equations:
An  equation uses mathematical operators to relate one set of variables or number to another set of variables or numbers.
Equation | Relation
:--------: | :-----:
2 + 2 = 4 | A simple equation
y = mx + c | A Straight line
ax^2^ + bx + c = 0 | A quadratic equation
(x-a)^2^ + (y-b) ^2^ = r^2^ | (A circle of radius with center a,b).

We often have to simplify equations. The most effective way of simplifying an equation is to add up similar terms and ordering the powers.
Equation | Conversion
:-------------------------------: | :-:
(n-1)(n-2)(n-3)=(n2-2n-n+2)(n-3)=(n2-3n+2)(n-3)=n3-3n2-3n2+9n+2n-6 | n3-6n2+11n-6
This equation is commonly, and wrongly seen as NxNxN = 3N

## Function:
A function is a relation that uniquely associates members of one set with members of another set:
Note | Example:
:--------: | :-----:
Functions can take parameters | f(x,y)= 2x+y
Functions can be many to one | f(x) = 7
Functions can be one to one | f(x) = 7x + 3.21
Functions can be one to many | f(x) = √x

One of the most popular functions is the exponential function.

Equation | Output:
:--------: | :-----:
_f_(x) = exp(x) = e^x^ | ![Image result for exponential function](http://mathworld.wolfram.com/images/interactive/ExpReal.gif)

## Subscript:
A subscript is a natural number that indexes a list of variables. For example:
- Let X be the list (or vector) [x~1~,...,x~n~], then to access any element we use the notation x~i~, where 1 ≤ i  ≤ n
- We use the notation |X| to refer to the number of elements in the list X, which is n in this case

-  If X = [5,2,-8,3.6,88,2000.003]
	- Then x~1~=5, x~2~ = 2, x~3~ = -8 
	- Note also that |X|=6
	- Note also that we use double subscripts for arrays (matrices)

## Summation:
Let X be the list [x~1~,...,x~n~], then if we want sum all of the elements up, we would use the notation:

Summation | Output:
:--------: | :-----:
![](https://latex.codecogs.com/gif.latex?%24%24S%20%3D%20%5Cdisplaystyle%5Csum_%7Bi%3D1%7D%5E%7BN%7D%20X_i%24%24) | S = X~1~ + X~2~ + X~3~+ ...X~n~

Note that we are arbitrarily assigning the result to s. If we wanted to sum the squares:

Summation | Output:
:--------: | :-----:
![](https://latex.codecogs.com/gif.latex?%24%24S%20%3D%20%5Cdisplaystyle%5Csum_%7Bi%3D1%7D%5E%7BN%7D%20X_i%20%5E%7B2%7D%24%24) |  S = X~1~^2^ + X~2~^2^ + X~3~^2^+ ...X~n~^2^

As with a for loop, the bottom value is the starting value, and the top value is the end value
Note that *i* can be replaced by any other variable name, as long as you are consistent.
By convention the variables *i,j and k* are often used for subscripts

## Products:
Let X be the list [x~1~,...,x~n~], then if we want multiple together all of the elements, we would use the notation:

Summation | Output:
:--------: | :-----:
![](https://latex.codecogs.com/gif.latex?%24%24S%20%3D%20%5Cdisplaystyle%5Cprod_%7Bi%3D1%7D%5E%7BN%7D%20X_i%24%24) |  S = X~1~X~2~X~3~...X~n~

Note that we are arbitrarily assigning the result to s. If we wanted to sum the squares:

Summation | Output:
:--------: | :-----:
![](https://latex.codecogs.com/gif.latex?%24%24S%20%3D%20%5Cdisplaystyle%5Cprod_%7Bi%3D1%7D%5E%7BN%7D%20X_i%20%5E%7B2%7D%24%24) |  S = X ~1~ ^2^ X ~2~ ^2^ X ~3~ ^2^ ... X ~n~ ^2^
