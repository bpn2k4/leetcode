
<h3>Regions Cut By Slashes</h3>
<div><p>An <code>n x n</code> grid is composed of <code>1 x 1</code> squares where each <code>1 x 1</code> square consists of a <code>'/'</code>, <code>'\'</code>, or blank space <code>' '</code>. These characters divide the square into contiguous regions.</p>
<p>Given the grid <code>grid</code> represented as a string array, return <em>the number of regions</em>.</p>
<p>Note that backslash characters are escaped, so a <code>'\'</code> is represented as <code>'\\'</code>.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<img alt="" src="assets/6fc4b6bcccb646d0b7740dcb57bd726b.png" style="width: 200px; height: 200px;"/>
<pre><strong>Input:</strong> grid = [" /","/ "]
<strong>Output:</strong> 2
</pre>
<p><strong>Example 2:</strong></p>
<img alt="" src="assets/b619e24a31a344489a98b2720e899cf2.png" style="width: 200px; height: 198px;"/>
<pre><strong>Input:</strong> grid = [" /","  "]
<strong>Output:</strong> 1
</pre>
<p><strong>Example 3:</strong></p>
<img alt="" src="assets/1c9d97e9abdc4a0f9578c5c03067a9a6.png" style="width: 200px; height: 200px;"/>
<pre><strong>Input:</strong> grid = ["/\\","\\/"]
<strong>Output:</strong> 5
<strong>Explanation: </strong>Recall that because \ characters are escaped, "\\/" refers to \/, and "/\\" refers to /\.
</pre>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>n == grid.length == grid[i].length</code></li>
<li><code>1 &lt;= n &lt;= 30</code></li>
<li><code>grid[i][j]</code> is either <code>'/'</code>, <code>'\'</code>, or <code>' '</code>.</li>
</ul>
</div>
