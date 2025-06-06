
<h3>Set Matrix Zeroes</h3>
<div><p>Given an <code>m x n</code> integer matrix <code>matrix</code>, if an element is <code>0</code>, set its entire row and column to <code>0</code>'s.</p>
<p>You must do it <a href="https://en.wikipedia.org/wiki/In-place_algorithm" target="_blank">in place</a>.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<img alt="" src="assets/c249411928cb4546a0f268e8e456ae37.jpg" style="width: 450px; height: 169px;"/>
<pre><strong>Input:</strong> matrix = [[1,1,1],[1,0,1],[1,1,1]]
<strong>Output:</strong> [[1,0,1],[0,0,0],[1,0,1]]
</pre>
<p><strong>Example 2:</strong></p>
<img alt="" src="assets/133ed2580f9e4dd4abfa70a80c8d77b1.jpg" style="width: 450px; height: 137px;"/>
<pre><strong>Input:</strong> matrix = [[0,1,2,0],[3,4,5,2],[1,3,1,5]]
<strong>Output:</strong> [[0,0,0,0],[0,4,5,0],[0,3,1,0]]
</pre>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>m == matrix.length</code></li>
<li><code>n == matrix[0].length</code></li>
<li><code>1 &lt;= m, n &lt;= 200</code></li>
<li><code>-2<sup>31</sup> &lt;= matrix[i][j] &lt;= 2<sup>31</sup> - 1</code></li>
</ul>
<p> </p>
<p><strong>Follow up:</strong></p>
<ul>
<li>A straightforward solution using <code>O(mn)</code> space is probably a bad idea.</li>
<li>A simple improvement uses <code>O(m + n)</code> space, but still not the best solution.</li>
<li>Could you devise a constant space solution?</li>
</ul>
</div>
