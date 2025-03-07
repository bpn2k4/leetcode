
<h3>Maximum Matrix Sum</h3>
<div><p>You are given an <code>n x n</code> integer <code>matrix</code>. You can do the following operation <strong>any</strong> number of times:</p>
<ul>
<li>Choose any two <strong>adjacent</strong> elements of <code>matrix</code> and <strong>multiply</strong> each of them by <code>-1</code>.</li>
</ul>
<p>Two elements are considered <strong>adjacent</strong> if and only if they share a <strong>border</strong>.</p>
<p>Your goal is to <strong>maximize</strong> the summation of the matrix's elements. Return <em>the <strong>maximum</strong> sum of the matrix's elements using the operation mentioned above.</em></p>
<p> </p>
<p><strong>Example 1:</strong></p>
<img alt="" src="assets/80eddcb2cdd1475bb9abdc08c198381f.png" style="width: 401px; height: 81px;"/>
<pre><strong>Input:</strong> matrix = [[1,-1],[-1,1]]
<strong>Output:</strong> 4
<b>Explanation:</b> We can follow the following steps to reach sum equals 4:
- Multiply the 2 elements in the first row by -1.
- Multiply the 2 elements in the first column by -1.
</pre>
<p><strong>Example 2:</strong></p>
<img alt="" src="assets/d322f9c436a64da5be9d2422c738979a.png" style="width: 321px; height: 121px;"/>
<pre><strong>Input:</strong> matrix = [[1,2,3],[-1,-2,-3],[1,2,3]]
<strong>Output:</strong> 16
<b>Explanation:</b> We can follow the following step to reach sum equals 16:
- Multiply the 2 last elements in the second row by -1.
</pre>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>n == matrix.length == matrix[i].length</code></li>
<li><code>2 &lt;= n &lt;= 250</code></li>
<li><code>-10<sup>5</sup> &lt;= matrix[i][j] &lt;= 10<sup>5</sup></code></li>
</ul>
</div>
