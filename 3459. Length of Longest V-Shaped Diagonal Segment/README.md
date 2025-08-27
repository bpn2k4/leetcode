
<h3>Length of Longest V-Shaped Diagonal Segment</h3>
<div><p>You are given a 2D integer matrix <code>grid</code> of size <code>n x m</code>, where each element is either <code>0</code>, <code>1</code>, or <code>2</code>.</p>
<p>A <strong>V-shaped diagonal segment</strong> is defined as:</p>
<ul>
<li>The segment starts with <code>1</code>.</li>
<li>The subsequent elements follow this infinite sequence: <code>2, 0, 2, 0, ...</code>.</li>
<li>The segment:
	<ul>
<li>Starts <strong>along</strong> a diagonal direction (top-left to bottom-right, bottom-right to top-left, top-right to bottom-left, or bottom-left to top-right).</li>
<li>Continues the<strong> sequence</strong> in the same diagonal direction.</li>
<li>Makes<strong> at most one clockwise 90-degree</strong><strong> turn</strong> to another diagonal direction while <strong>maintaining</strong> the sequence.</li>
</ul>
</li>
</ul>
<p><img alt="" src="assets/5761b1f5236043e4b7e3bf7a9f2a699b.jpg" style="width: 481px; height: 202px;"/></p>
<p>Return the <strong>length</strong> of the <strong>longest</strong> <strong>V-shaped diagonal segment</strong>. If no valid segment <em>exists</em>, return 0.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">grid = [[2,2,1,2,2],[2,0,2,2,0],[2,0,1,1,0],[1,0,2,2,2],[2,0,0,2,2]]</span></p>
<p><strong>Output:</strong> <span class="example-io">5</span></p>
<p><strong>Explanation:</strong></p>
<p><img alt="" src="assets/1d14e32d52e3439181585846001d35b4.jpg" style="width: 201px; height: 192px;"/></p>
<p>The longest V-shaped diagonal segment has a length of 5 and follows these coordinates: <code>(0,2) → (1,3) → (2,4)</code>, takes a <strong>90-degree clockwise turn</strong> at <code>(2,4)</code>, and continues as <code>(3,3) → (4,2)</code>.</p>
</div>
<p><strong>Example 2:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">grid = [[2,2,2,2,2],[2,0,2,2,0],[2,0,1,1,0],[1,0,2,2,2],[2,0,0,2,2]]</span></p>
<p><strong>Output:</strong> <span class="example-io">4</span></p>
<p><strong>Explanation:</strong></p>
<p><strong><img alt="" src="assets/2b4ee70aaf4b41f293011e9cd2df0bec.jpg" style="width: 201px; height: 201px;"/></strong></p>
<p>The longest V-shaped diagonal segment has a length of 4 and follows these coordinates: <code>(2,3) → (3,2)</code>, takes a <strong>90-degree clockwise turn</strong> at <code>(3,2)</code>, and continues as <code>(2,1) → (1,0)</code>.</p>
</div>
<p><strong>Example 3:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">grid = [[1,2,2,2,2],[2,2,2,2,0],[2,0,0,0,0],[0,0,2,2,2],[2,0,0,2,0]]</span></p>
<p><strong>Output:</strong> <span class="example-io">5</span></p>
<p><strong>Explanation:</strong></p>
<p><strong><img alt="" src="assets/46b8a6f288344b2b835d3f479e12cddb.jpg" style="width: 201px; height: 201px;"/></strong></p>
<p>The longest V-shaped diagonal segment has a length of 5 and follows these coordinates: <code>(0,0) → (1,1) → (2,2) → (3,3) → (4,4)</code>.</p>
</div>
<p><strong>Example 4:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">grid = [[1]]</span></p>
<p><strong>Output:</strong> <span class="example-io">1</span></p>
<p><strong>Explanation:</strong></p>
<p>The longest V-shaped diagonal segment has a length of 1 and follows these coordinates: <code>(0,0)</code>.</p>
</div>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>n == grid.length</code></li>
<li><code>m == grid[i].length</code></li>
<li><code>1 &lt;= n, m &lt;= 500</code></li>
<li><code>grid[i][j]</code> is either <code>0</code>, <code>1</code> or <code>2</code>.</li>
</ul>
</div>
