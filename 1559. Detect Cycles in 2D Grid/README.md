
<h3>Detect Cycles in 2D Grid</h3>
<div class="HTMLContent_html__0OZLp" data-track-load="description_content"><p>Given a 2D array of characters <code>grid</code> of size <code>m x n</code>, you need to find if there exists any cycle consisting of the <strong>same value</strong> in <code>grid</code>.</p>
<p>A cycle is a path of <strong>length 4 or more</strong> in the grid that starts and ends at the same cell. From a given cell, you can move to one of the cells adjacent to it - in one of the four directions (up, down, left, or right), if it has the <strong>same value</strong> of the current cell.</p>
<p>Also, you cannot move to the cell that you visited in your last move. For example, the cycle <code>(1, 1) -&gt; (1, 2) -&gt; (1, 1)</code> is invalid because from <code>(1, 2)</code> we visited <code>(1, 1)</code> which was the last visited cell.</p>
<p>Return <code>true</code> if any cycle of the same value exists in <code>grid</code>, otherwise, return <code>false</code>.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<p><strong><img alt="" src="assets/d9fc50de176141a5ba0db268d72657eb.png" style="width: 231px; height: 152px;"/></strong></p>
<pre><strong>Input:</strong> grid = [["a","a","a","a"],["a","b","b","a"],["a","b","b","a"],["a","a","a","a"]]
<strong>Output:</strong> true
<strong>Explanation: </strong>There are two valid cycles shown in different colors in the image below:
<img alt="" src="assets/a7582d8fd2e441d08d6e9a31ef0ce907.png" style="width: 225px; height: 163px;"/>
</pre>
<p><strong>Example 2:</strong></p>
<p><strong><img alt="" src="assets/3a3d2d2fae3e42548b9c427895436a42.png" style="width: 236px; height: 154px;"/></strong></p>
<pre><strong>Input:</strong> grid = [["c","c","c","a"],["c","d","c","c"],["c","c","e","c"],["f","c","c","c"]]
<strong>Output:</strong> true
<strong>Explanation: </strong>There is only one valid cycle highlighted in the image below:
<img alt="" src="assets/01487be48c8d40f28afbd3af971d0766.png" style="width: 229px; height: 157px;"/>
</pre>
<p><strong>Example 3:</strong></p>
<p><strong><img alt="" src="assets/67a82e92bf1d42e39d543cc9f902db39.png" style="width: 183px; height: 120px;"/></strong></p>
<pre><strong>Input:</strong> grid = [["a","b","b"],["b","z","b"],["b","b","a"]]
<strong>Output:</strong> false
</pre>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>m == grid.length</code></li>
<li><code>n == grid[i].length</code></li>
<li><code>1 &lt;= m, n &lt;= 500</code></li>
<li><code>grid</code> consists only of lowercase English letters.</li>
</ul>
</div>
