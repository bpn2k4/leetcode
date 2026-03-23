
<h3>Maximum Non Negative Product in a Matrix</h3>
<div><p>You are given a <code>m x n</code> matrix <code>grid</code>. Initially, you are located at the top-left corner <code>(0, 0)</code>, and in each step, you can only <strong>move right or down</strong> in the matrix.</p>
<p>Among all possible paths starting from the top-left corner <code>(0, 0)</code> and ending in the bottom-right corner <code>(m - 1, n - 1)</code>, find the path with the <strong>maximum non-negative product</strong>. The product of a path is the product of all integers in the grid cells visited along the path.</p>
<p>Return the <em>maximum non-negative product <strong>modulo</strong> </em><code>10<sup>9</sup> + 7</code>. <em>If the maximum product is <strong>negative</strong>, return </em><code>-1</code>.</p>
<p>Notice that the modulo is performed after getting the maximum product.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<img alt="" src="assets/9fe90b99758c4c41808dfe552ba7dc65.jpg" style="width: 244px; height: 245px;"/>
<pre><strong>Input:</strong> grid = [[-1,-2,-3],[-2,-3,-3],[-3,-3,-2]]
<strong>Output:</strong> -1
<strong>Explanation:</strong> It is not possible to get non-negative product in the path from (0, 0) to (2, 2), so return -1.
</pre>
<p><strong>Example 2:</strong></p>
<img alt="" src="assets/2efeab00bd5f45978d3079de6d526a7e.jpg" style="width: 244px; height: 245px;"/>
<pre><strong>Input:</strong> grid = [[1,-2,1],[1,-2,1],[3,-4,1]]
<strong>Output:</strong> 8
<strong>Explanation:</strong> Maximum non-negative product is shown (1 * 1 * -2 * -4 * 1 = 8).
</pre>
<p><strong>Example 3:</strong></p>
<img alt="" src="assets/3f5e213139bd4abd8ab5b732e6872805.jpg" style="width: 164px; height: 165px;"/>
<pre><strong>Input:</strong> grid = [[1,3],[0,-4]]
<strong>Output:</strong> 0
<strong>Explanation:</strong> Maximum non-negative product is shown (1 * 0 * -4 = 0).
</pre>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>m == grid.length</code></li>
<li><code>n == grid[i].length</code></li>
<li><code>1 &lt;= m, n &lt;= 15</code></li>
<li><code>-4 &lt;= grid[i][j] &lt;= 4</code></li>
</ul>
</div>
