
<h3>Cyclically Rotating a Grid</h3>
<div class="HTMLContent_html__0OZLp" data-track-load="description_content"><p>You are given an <code>m x n</code> integer matrix <code>grid</code>​​​, where <code>m</code> and <code>n</code> are both <strong>even</strong> integers, and an integer <code>k</code>.</p>
<p>The matrix is composed of several layers, which is shown in the below image, where each color is its own layer:</p>
<p><img alt="" src="assets/11d996342c9941f4a2b24d7003320431.png" style="width: 231px; height: 258px;"/></p>
<p>A cyclic rotation of the matrix is done by cyclically rotating <strong>each layer</strong> in the matrix. To cyclically rotate a layer once, each element in the layer will take the place of the adjacent element in the <strong>counter-clockwise</strong> direction. An example rotation is shown below:</p>
<img alt="" src="assets/0a0b9d92f755446887b2d269c4c094da.jpg" style="width: 500px; height: 268px;"/>
<p>Return <em>the matrix after applying </em><code>k</code> <em>cyclic rotations to it</em>.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<img alt="" src="assets/89a5eeb16ffa4c0d896a317ce4c55eda.png" style="width: 421px; height: 191px;"/>
<pre><strong>Input:</strong> grid = [[40,10],[30,20]], k = 1
<strong>Output:</strong> [[10,20],[40,30]]
<strong>Explanation:</strong> The figures above represent the grid at every state.
</pre>
<p><strong>Example 2:</strong></p>
<strong><img alt="" src="assets/79f4feb85b2a454896438bd4cc8a1e8d.png" style="width: 231px; height: 262px;"/></strong> <strong><img alt="" src="assets/5ef83c823e4748ca99af08257a2372f3.png" style="width: 231px; height: 262px;"/></strong> <strong><img alt="" src="assets/f4bf3e7936194ba1a7f293baeb7f922d.png" style="width: 231px; height: 262px;"/></strong>
<pre><strong>Input:</strong> grid = [[1,2,3,4],[5,6,7,8],[9,10,11,12],[13,14,15,16]], k = 2
<strong>Output:</strong> [[3,4,8,12],[2,11,10,16],[1,7,6,15],[5,9,13,14]]
<strong>Explanation:</strong> The figures above represent the grid at every state.
</pre>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>m == grid.length</code></li>
<li><code>n == grid[i].length</code></li>
<li><code>2 &lt;= m, n &lt;= 50</code></li>
<li>Both <code>m</code> and <code>n</code> are <strong>even</strong> integers.</li>
<li><code>1 &lt;= grid[i][j] &lt;=<sup> </sup>5000</code></li>
<li><code>1 &lt;= k &lt;= 10<sup>9</sup></code></li>
</ul></div>
