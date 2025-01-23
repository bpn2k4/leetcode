
<h3>Count Servers that Communicate</h3>
<div><p>You are given a map of a server center, represented as a <code>m * n</code> integer matrix <code>grid</code>, where 1 means that on that cell there is a server and 0 means that it is no server. Two servers are said to communicate if they are on the same row or on the same column.<br/>
<br/>
Return the number of servers that communicate with any other server.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<p><img alt="" src="assets/89ce6713863c461c84364eb4eba74ba1.jpg" style="width: 202px; height: 203px;"/></p>
<pre><strong>Input:</strong> grid = [[1,0],[0,1]]
<strong>Output:</strong> 0
<b>Explanation:</b> No servers can communicate with others.</pre>
<p><strong>Example 2:</strong></p>
<p><strong><img alt="" src="assets/f479b35b0aef4e9492e79f1d5e45baca.jpg" style="width: 203px; height: 203px;"/></strong></p>
<pre><strong>Input:</strong> grid = [[1,0],[1,1]]
<strong>Output:</strong> 3
<b>Explanation:</b> All three servers can communicate with at least one other server.
</pre>
<p><strong>Example 3:</strong></p>
<p><img alt="" src="assets/9c75ee52cf9046368fbb7a46f92dae65.jpg" style="width: 443px; height: 443px;"/></p>
<pre><strong>Input:</strong> grid = [[1,1,0,0],[0,0,1,0],[0,0,1,0],[0,0,0,1]]
<strong>Output:</strong> 4
<b>Explanation:</b> The two servers in the first row can communicate with each other. The two servers in the third column can communicate with each other. The server at right bottom corner can't communicate with any other server.
</pre>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>m == grid.length</code></li>
<li><code>n == grid[i].length</code></li>
<li><code>1 &lt;= m &lt;= 250</code></li>
<li><code>1 &lt;= n &lt;= 250</code></li>
<li><code>grid[i][j] == 0 or 1</code></li>
</ul>
</div>
