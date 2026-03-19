
<h3>Count Submatrices With Equal Frequency of X and Y</h3>
<div><p>Given a 2D character matrix <code>grid</code>, where <code>grid[i][j]</code> is either <code>'X'</code>, <code>'Y'</code>, or <code>'.'</code>, return the number of <span class="cursor-pointer relative text-dark-blue-s text-sm" data-keyword="submatrix"><button aria-controls="radix-:r1k:" aria-expanded="false" aria-haspopup="dialog" class="" data-state="closed" type="button">submatrices</button></span> that contain:</p>
<ul>
<li><code>grid[0][0]</code></li>
<li>an <strong>equal</strong> frequency of <code>'X'</code> and <code>'Y'</code>.</li>
<li><strong>at least</strong> one <code>'X'</code>.</li>
</ul>
<p> </p>
<p><strong>Example 1:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">grid = [["X","Y","."],["Y",".","."]]</span></p>
<p><strong>Output:</strong> <span class="example-io">3</span></p>
<p><strong>Explanation:</strong></p>
<p><strong><img alt="" src="assets/2fa8fd113b814544a38d2d6a30a52bf5.png" style="padding: 10px; background: rgb(255, 255, 255); border-radius: 0.5rem; width: 175px; height: 350px;"/></strong></p>
</div>
<p><strong>Example 2:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">grid = [["X","X"],["X","Y"]]</span></p>
<p><strong>Output:</strong> <span class="example-io">0</span></p>
<p><strong>Explanation:</strong></p>
<p>No submatrix has an equal frequency of <code>'X'</code> and <code>'Y'</code>.</p>
</div>
<p><strong>Example 3:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">grid = [[".","."],[".","."]]</span></p>
<p><strong>Output:</strong> <span class="example-io">0</span></p>
<p><strong>Explanation:</strong></p>
<p>No submatrix has at least one <code>'X'</code>.</p>
</div>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>1 &lt;= grid.length, grid[i].length &lt;= 1000</code></li>
<li><code>grid[i][j]</code> is either <code>'X'</code>, <code>'Y'</code>, or <code>'.'</code>.</li>
</ul>
</div>
