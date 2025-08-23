
<h3>Find the Minimum Area to Cover All Ones II</h3>
<div><p>You are given a 2D <strong>binary</strong> array <code>grid</code>. You need to find 3 <strong>non-overlapping</strong> rectangles having <strong>non-zero</strong> areas with horizontal and vertical sides such that all the 1's in <code>grid</code> lie inside these rectangles.</p>
<p>Return the <strong>minimum</strong> possible sum of the area of these rectangles.</p>
<p><strong>Note</strong> that the rectangles are allowed to touch.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">grid = [[1,0,1],[1,1,1]]</span></p>
<p><strong>Output:</strong> <span class="example-io">5</span></p>
<p><strong>Explanation:</strong></p>
<p><img alt="" src="assets/21b0dae7d67b458e867b4596ac99ff27.png" style="padding: 10px; background: rgb(255, 255, 255); border-radius: 0.5rem; width: 280px; height: 198px;"/></p>
<ul>
<li>The 1's at <code>(0, 0)</code> and <code>(1, 0)</code> are covered by a rectangle of area 2.</li>
<li>The 1's at <code>(0, 2)</code> and <code>(1, 2)</code> are covered by a rectangle of area 2.</li>
<li>The 1 at <code>(1, 1)</code> is covered by a rectangle of area 1.</li>
</ul>
</div>
<p><strong>Example 2:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">grid = [[1,0,1,0],[0,1,0,1]]</span></p>
<p><strong>Output:</strong> <span class="example-io">5</span></p>
<p><strong>Explanation:</strong></p>
<p><img alt="" src="assets/1eb4d1073bf94050bf1ca52398b69af4.png" style="padding: 10px; background: rgb(255, 255, 255); border-radius: 0.5rem; width: 356px; height: 198px;"/></p>
<ul>
<li>The 1's at <code>(0, 0)</code> and <code>(0, 2)</code> are covered by a rectangle of area 3.</li>
<li>The 1 at <code>(1, 1)</code> is covered by a rectangle of area 1.</li>
<li>The 1 at <code>(1, 3)</code> is covered by a rectangle of area 1.</li>
</ul>
</div>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>1 &lt;= grid.length, grid[i].length &lt;= 30</code></li>
<li><code>grid[i][j]</code> is either 0 or 1.</li>
<li>The input is generated such that there are at least three 1's in <code>grid</code>.</li>
</ul>
</div>
