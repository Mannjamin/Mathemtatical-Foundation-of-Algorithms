<h1><a id="The_Mathematical_Foundations_of_Algorithms_0"></a>The Mathematical Foundations of Algorithms</h1>
<h2><a id="Table_of_Contents_2"></a>Table of Contents:</h2>
<ul>
<li>Variables</li>
<li>Sets</li>
<li>Equations</li>
<li>Functions</li>
<li>Subscripts</li>
<li>Summation</li>
<li>Products
<ul>
<li>And more!</li>
</ul>
</li>
</ul>
<h2><a id="Variables_13"></a>Variables:</h2>
<p>A variable is a symbol used to represent a mathematical construct</p>
<blockquote>
<p>Numbers, sets, lists , vectors, matrices, …</p>
</blockquote>
<p>Often lower case letters or Greek letters are used</p>
<blockquote>
<p><em>x, y, z,</em> Ω, <em>α</em>, β, …</p>
</blockquote>
<p>Variables in Mathematics are treated the same as variables within a programming language. They can be thought of as a box containing a value that can be read from or written to.</p>
<h2><a id="Sets_22"></a>Sets:</h2>
<ul>
<li>A set is a finite or infinite collection of items.</li>
<li>A set has no order.</li>
<li>You cannot index a set…</li>
<li>A set only contains one copy of an item.</li>
</ul>
<table class="table table-striped table-bordered">
<thead>
<tr>
<th style="text-align:center">Symbol</th>
<th style="text-align:center">Name</th>
<th style="text-align:center">Meaning / Definition</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">a ∈ A</td>
<td style="text-align:center">Element of</td>
<td style="text-align:center">Item is a member of set A.</td>
</tr>
<tr>
<td style="text-align:center">a ∉ A</td>
<td style="text-align:center">Not Element of</td>
<td style="text-align:center">Item is not a member of set A.</td>
</tr>
<tr>
<td style="text-align:center">Ø</td>
<td style="text-align:center">Empty Set</td>
<td style="text-align:center">Represents an Empty Set.</td>
</tr>
<tr>
<td style="text-align:center"><em>/A/</em></td>
<td style="text-align:center">Cardinality</td>
<td style="text-align:center">The number of elements of set A.</td>
</tr>
<tr>
<td style="text-align:center"><strong><em>R</em></strong></td>
<td style="text-align:center">Real Numbers</td>
<td style="text-align:center">A set of Real Numbers.</td>
</tr>
<tr>
<td style="text-align:center"><strong><em>Z</em></strong></td>
<td style="text-align:center">Integers</td>
<td style="text-align:center">A set of Integers.</td>
</tr>
<tr>
<td style="text-align:center"><strong><em>N</em></strong></td>
<td style="text-align:center">Natural Numbers</td>
<td style="text-align:center">A set of Natural Numbers.</td>
</tr>
</tbody>
</table>
<blockquote>
<p>The entire alphabet can be used to define a set.<br>
<a href="https://www.rapidtables.com/math/symbols/Basic_Math_Symbols.html">You can find more Mathematical Symbol Meanings here</a>.</p>
</blockquote>
<h3><a id="Set_Operators_42"></a>Set Operators:</h3>
<h4><a id="Creating_A_Set_44"></a>Creating A Set:</h4>
<p>The process of defining a set:</p>
<ol>
<li>A = {variable : inclusion criteria}.</li>
<li>A = {n<sup>2</sup> : n is an integer and 0 ≤ n ≤ 5}.</li>
<li>A = {0, 1, 4, 9, 16, 25}.</li>
</ol>
<h4><a id="Unifying_a_set_51"></a>Unifying a set:</h4>
<p>The process of unifying a set:</p>
<ol>
<li>A = B ∪ C.</li>
<li>A = <em>{a : a ∪ B <strong>OR</strong> a ∈ C}</em>.</li>
<li>A contains all of B and C.</li>
</ol>
<h4><a id="Intersection_of_a_set_58"></a>Intersection of a set:</h4>
<p>The process of Intersection:</p>
<ol>
<li>A = B  ∩  C</li>
<li>A = <em>{a : a ∈ B <strong>AND</strong> a ∈ C}</em></li>
<li>A contains only what B and C have in common</li>
</ol>
<h4><a id="Subsets_and_Superset_65"></a>Subsets and Superset:</h4>
<h5><a id="If_A_is_a_Set_66"></a>If A is a Set:</h5>
<table class="table table-striped table-bordered">
<thead>
<tr>
<th style="text-align:center">Symbol</th>
<th style="text-align:center">Name</th>
<th style="text-align:center">Meaning / Definition</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">B ⊆ A</td>
<td style="text-align:center">Subset</td>
<td style="text-align:center">B ⊆ A means B is a Subset of A <strong>AND</strong> Set B is included in Set A.</td>
</tr>
<tr>
<td style="text-align:center">B ⊂ A</td>
<td style="text-align:center">Proper/Strict Subset</td>
<td style="text-align:center">B is a subset of A, but B is not equal to A.</td>
</tr>
<tr>
<td style="text-align:center">B ⊇ A</td>
<td style="text-align:center">Superset</td>
<td style="text-align:center">B is a Superset of A. Set-B includes Set-A.</td>
</tr>
<tr>
<td style="text-align:center">A ⊅ B</td>
<td style="text-align:center">Not a Superset</td>
<td style="text-align:center">Set-B is not a superset of Set-A</td>
</tr>
</tbody>
</table>
<h4><a id="Subtraction_74"></a>Subtraction:</h4>
<p>The process of Subtraction:</p>
<ol>
<li>A = C\B.</li>
<li>A = <em>{a : a ∈ C <strong>AND</strong> a ∉ B}.</em></li>
<li>A is B with all the elements of C removed</li>
</ol>
<h2><a id="Equations_81"></a>Equations:</h2>
<p>An  equation uses mathematical operators to relate one set of variables or number to another set of variables or numbers.</p>
<table class="table table-striped table-bordered">
<thead>
<tr>
<th style="text-align:center">Equation</th>
<th style="text-align:center">Relation</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">2 + 2 = 4</td>
<td style="text-align:center">A simple equation</td>
</tr>
<tr>
<td style="text-align:center">y = mx + c</td>
<td style="text-align:center">A Straight line</td>
</tr>
<tr>
<td style="text-align:center">ax<sup>2</sup> + bx + c = 0</td>
<td style="text-align:center">A quadratic equation</td>
</tr>
<tr>
<td style="text-align:center">(x-a)<sup>2</sup> + (y-b) <sup>2</sup> = r<sup>2</sup></td>
<td style="text-align:center">(A circle of radius with center a,b).</td>
</tr>
</tbody>
</table>
<p>We often have to simplify equations. The most effective way of simplifying an equation is to add up similar terms and ordering the powers.</p>
<table class="table table-striped table-bordered">
<thead>
<tr>
<th style="text-align:center">Equation</th>
<th style="text-align:center">Conversion</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">(n-1)(n-2)(n-3)=(n2-2n-n+2)(n-3)=(n2-3n+2)(n-3)=n3-3n2-3n2+9n+2n-6</td>
<td style="text-align:center">n3-6n2+11n-6</td>
</tr>
</tbody>
</table>
<p>This equation is commonly, and wrongly seen as NxNxN = 3N</p>
<h2><a id="Function_96"></a>Function:</h2>
<p>A function is a relation that uniquely associates members of one set with members of another set:</p>
<table class="table table-striped table-bordered">
<thead>
<tr>
<th style="text-align:center">Note</th>
<th style="text-align:center">Example:</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Functions can take parameters</td>
<td style="text-align:center">f(x,y)= 2x+y</td>
</tr>
<tr>
<td style="text-align:center">Functions can be many to one</td>
<td style="text-align:center">f(x) = 7</td>
</tr>
<tr>
<td style="text-align:center">Functions can be one to one</td>
<td style="text-align:center">f(x) = 7x + 3.21</td>
</tr>
<tr>
<td style="text-align:center">Functions can be one to many</td>
<td style="text-align:center">f(x) = √x</td>
</tr>
</tbody>
</table>
<p>One of the most popular functions is the exponential function.</p>
<table class="table table-striped table-bordered">
<thead>
<tr>
<th style="text-align:center">Equation</th>
<th style="text-align:center">Output:</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center"><em>f</em>(x) = exp(x) = e<sup>x</sup></td>
<td style="text-align:center"><img src="http://mathworld.wolfram.com/images/interactive/ExpReal.gif" alt="Image result for exponential function"></td>
</tr>
</tbody>
</table>
<h2><a id="Subscript_111"></a>Subscript:</h2>
<p>A subscript is a natural number that indexes a list of variables. For example:</p>
<ul>
<li>
<p>Let X be the list (or vector) [x<sub>1</sub>,…,x<sub>n</sub>], then to access any element we use the notation x<sub>i</sub>, where 1 ≤ i  ≤ n</p>
</li>
<li>
<p>We use the notation |X| to refer to the number of elements in the list X, which is n in this case</p>
</li>
<li>
<p>If X = [5,2,-8,3.6,88,2000.003]</p>
<ul>
<li>Then x<sub>1</sub>=5, x<sub>2</sub> = 2, x<sub>3</sub> = -8</li>
<li>Note also that |X|=6</li>
<li>Note also that we use double subscripts for arrays (matrices)</li>
</ul>
</li>
</ul>
<h2><a id="Summation_121"></a>Summation:</h2>
<p>Let X be the list [x<sub>1</sub>,…,x<sub>n</sub>], then if we want sum all of the elements up, we would use the notation:</p>
<table class="table table-striped table-bordered">
<thead>
<tr>
<th style="text-align:center">Summation</th>
<th style="text-align:center">Output:</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center"><img src="https://latex.codecogs.com/gif.latex?%24%24S%20%3D%20%5Cdisplaystyle%5Csum_%7Bi%3D1%7D%5E%7BN%7D%20X_i%24%24" alt=""></td>
<td style="text-align:center">S = X<sub>1</sub> + X<sub>2</sub> + X<sub>3</sub>+ …X<sub>n</sub></td>
</tr>
</tbody>
</table>
<p>Note that we are arbitrarily assigning the result to s. If we wanted to sum the squares:</p>
<table class="table table-striped table-bordered">
<thead>
<tr>
<th style="text-align:center">Summation</th>
<th style="text-align:center">Output:</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center"><img src="https://latex.codecogs.com/gif.latex?%24%24S%20%3D%20%5Cdisplaystyle%5Csum_%7Bi%3D1%7D%5E%7BN%7D%20X_i%20%5E%7B2%7D%24%24" alt=""></td>
<td style="text-align:center">S = X<sub>1</sub><sup>2</sup> + X<sub>2</sub><sup>2</sup> + X<sub>3</sub><sup>2</sup>+ …X<sub>n</sub><sup>2</sup></td>
</tr>
</tbody>
</table>
<p>As with a for loop, the bottom value is the starting value, and the top value is the end value<br>
Note that <em>i</em> can be replaced by any other variable name, as long as you are consistent.<br>
By convention the variables <em>i,j and k</em> are often used for subscripts</p>
<h2><a id="Products_135"></a>Products:</h2>
<p>Let X be the list [x<sub>1</sub>,…,x<sub>n</sub>], then if we want multiple together all of the elements, we would use the notation:</p>
<table class="table table-striped table-bordered">
<thead>
<tr>
<th style="text-align:center">Summation</th>
<th style="text-align:center">Output:</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center"><img src="https://latex.codecogs.com/gif.latex?%24%24S%20%3D%20%5Cdisplaystyle%5Cprod_%7Bi%3D1%7D%5E%7BN%7D%20X_i%24%24" alt=""></td>
<td style="text-align:center">S = X<sub>1</sub>X<sub>2</sub>X<sub>3</sub>…X<sub>n</sub></td>
</tr>
</tbody>
</table>
<p>Note that we are arbitrarily assigning the result to s. If we wanted to sum the squares:</p>
<table class="table table-striped table-bordered">
<thead>
<tr>
<th style="text-align:center">Summation</th>
<th style="text-align:center">Output:</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center"><img src="https://latex.codecogs.com/gif.latex?%24%24S%20%3D%20%5Cdisplaystyle%5Cprod_%7Bi%3D1%7D%5E%7BN%7D%20X_i%20%5E%7B2%7D%24%24" alt=""></td>
<td style="text-align:center">S = X<sub>1</sub><sup>2</sup>X<sub>2</sub><sup>2</sup>X<sub>3</sub><sup>2</sup>…X<sub>n</sub><sup>2</sup></td>
</tr>
</tbody>
</table>
