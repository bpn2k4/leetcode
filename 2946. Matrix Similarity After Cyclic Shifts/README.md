
<h3>Matrix Similarity After Cyclic Shifts</h3>
<div class="HTMLContent_html__0OZLp" data-track-load="description_content"><p>You are given an <code>m x n</code> integer matrix <code>mat</code> and an integer <code>k</code>. The matrix rows are 0-indexed.</p>
<p>The following proccess happens <code>k</code> times:</p>
<ul>
<li><strong>Even-indexed</strong> rows (0, 2, 4, ...) are cyclically shifted to the left.</li>
</ul>
<p><img src="assets/ed4d95be9e4a492a8eef3f484c201882.jpg" style="width: 283px; height: 90px;"/></p>
<ul>
<li><strong>Odd-indexed</strong> rows (1, 3, 5, ...) are cyclically shifted to the right.</li>
</ul>
<p><img src="assets/80db51b1d36748a18432e77a44844927.jpg" style="width: 283px; height: 90px;"/></p>
<p>Return <code>true</code> if the final modified matrix after <code>k</code> steps is identical to the original matrix, and <code>false</code> otherwise.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">mat = [[1,2,3],[4,5,6],[7,8,9]], k = 4</span></p>
<p><strong>Output:</strong> <span class="example-io">false</span></p>
<p><strong>Explanation:</strong></p>
<p>In each step left shift is applied to rows 0 and 2 (even indices), and right shift to row 1 (odd index).</p>
<p><img src="assets/10cc4e9707d143c8bd86f7500b37eac0.jpg" style="width: 857px; height: 150px;"/></p>
</div>
<p><strong>Example 2:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">mat = [[1,2,1,2],[5,5,5,5],[6,3,6,3]], k = 2</span></p>
<p><strong>Output:</strong> <span class="example-io">true</span></p>
<p><strong>Explanation:</strong></p>
<p><img src="assets/89087ebb6aed47529a07250c0117b619.jpg" style="width: 632px; height: 150px;"/></p>
</div>
<p><strong>Example 3:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">mat = [[2,2],[2,2]], k = 3</span></p>
<p><strong>Output:</strong> <span class="example-io">true</span></p>
<p><strong>Explanation:</strong></p>
<p>As all the values are equal in the matrix, even after performing cyclic shifts the matrix will remain the same.</p>
</div>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>1 &lt;= mat.length &lt;= 25</code></li>
<li><code>1 &lt;= mat[i].length &lt;= 25</code></li>
<li><code>1 &lt;= mat[i][j] &lt;= 25</code></li>
<li><code>1 &lt;= k &lt;= 50</code></li>
</ul>
</div>
