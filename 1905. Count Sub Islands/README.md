
<h3>Count Sub Islands</h3>
<div><p>You are given two <code>m x n</code> binary matrices <code>grid1</code> and <code>grid2</code> containing only <code>0</code>'s (representing water) and <code>1</code>'s (representing land). An <strong>island</strong> is a group of <code>1</code>'s connected <strong>4-directionally</strong> (horizontal or vertical). Any cells outside of the grid are considered water cells.</p>
<p>An island in <code>grid2</code> is considered a <strong>sub-island </strong>if there is an island in <code>grid1</code> that contains <strong>all</strong> the cells that make up <strong>this</strong> island in <code>grid2</code>.</p>
<p>Return the <em><strong>number</strong> of islands in </em><code>grid2</code> <em>that are considered <strong>sub-islands</strong></em>.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<img alt="" src="assets/3d0c2cf539384786b9ba3ab864b310ab.png" style="width: 493px; height: 205px;"/>
<pre><strong>Input:</strong> grid1 = [[1,1,1,0,0],[0,1,1,1,1],[0,0,0,0,0],[1,0,0,0,0],[1,1,0,1,1]], grid2 = [[1,1,1,0,0],[0,0,1,1,1],[0,1,0,0,0],[1,0,1,1,0],[0,1,0,1,0]]
<strong>Output:</strong> 3
<strong>Explanation: </strong>In the picture above, the grid on the left is grid1 and the grid on the right is grid2.
The 1s colored red in grid2 are those considered to be part of a sub-island. There are three sub-islands.
</pre>
<p><strong>Example 2:</strong></p>
<img alt="" src="assets/694d8ef379ef4f328926eb942623d9ee.png" style="width: 491px; height: 201px;"/>
<pre><strong>Input:</strong> grid1 = [[1,0,1,0,1],[1,1,1,1,1],[0,0,0,0,0],[1,1,1,1,1],[1,0,1,0,1]], grid2 = [[0,0,0,0,0],[1,1,1,1,1],[0,1,0,1,0],[0,1,0,1,0],[1,0,0,0,1]]
<strong>Output:</strong> 2 
<strong>Explanation: </strong>In the picture above, the grid on the left is grid1 and the grid on the right is grid2.
The 1s colored red in grid2 are those considered to be part of a sub-island. There are two sub-islands.
</pre>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>m == grid1.length == grid2.length</code></li>
<li><code>n == grid1[i].length == grid2[i].length</code></li>
<li><code>1 &lt;= m, n &lt;= 500</code></li>
<li><code>grid1[i][j]</code> and <code>grid2[i][j]</code> are either <code>0</code> or <code>1</code>.</li>
</ul>
</div>
