
<h3>Magic Squares In Grid</h3>
<div><p>A <code>3 x 3</code> <strong>magic square</strong> is a <code>3 x 3</code> grid filled with distinct numbers <strong>from </strong>1<strong> to </strong>9 such that each row, column, and both diagonals all have the same sum.</p>
<p>Given a <code>row x col</code> <code>grid</code> of integers, how many <code>3 x 3</code> contiguous magic square subgrids are there?</p>
<p>Note: while a magic square can only contain numbers from 1 to 9, <code>grid</code> may contain numbers up to 15.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<img alt="" src="assets/b528965c0c1341be965189f24b7dab4a.jpg" style="width: 322px; height: 242px;"/>
<pre><strong>Input:</strong> grid = [[4,3,8,4],[9,5,1,9],[2,7,6,2]]
<strong>Output:</strong> 1
<strong>Explanation: </strong>
The following subgrid is a 3 x 3 magic square:
<img alt="" src="assets/81575bd21c14414692b8fff7051cf4b2.jpg" style="width: 242px; height: 242px;"/>
while this one is not:
<img alt="" src="assets/02eec1ac198744d392fbe18179ac1b89.jpg" style="width: 242px; height: 242px;"/>
In total, there is only one magic square inside the given grid.
</pre>
<p><strong>Example 2:</strong></p>
<pre><strong>Input:</strong> grid = [[8]]
<strong>Output:</strong> 0
</pre>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>row == grid.length</code></li>
<li><code>col == grid[i].length</code></li>
<li><code>1 &lt;= row, col &lt;= 10</code></li>
<li><code>0 &lt;= grid[i][j] &lt;= 15</code></li>
</ul>
</div>