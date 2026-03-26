
<h3>Equal Sum Grid Partition II</h3>
<div><p>You are given an <code>m x n</code> matrix <code>grid</code> of positive integers. Your task is to determine if it is possible to make <strong>either one horizontal or one vertical cut</strong> on the grid such that:</p>
<ul>
<li>Each of the two resulting sections formed by the cut is <strong>non-empty</strong>.</li>
<li>The sum of elements in both sections is <b>equal</b>, or can be made equal by discounting <strong>at most</strong> one single cell in total (from either section).</li>
<li>If a cell is discounted, the rest of the section must <strong>remain connected</strong>.</li>
</ul>
<p>Return <code>true</code> if such a partition exists; otherwise, return <code>false</code>.</p>
<p><strong>Note:</strong> A section is <strong>connected</strong> if every cell in it can be reached from any other cell by moving up, down, left, or right through other cells in the section.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">grid = [[1,4],[2,3]]</span></p>
<p><strong>Output:</strong> <span class="example-io">true</span></p>
<p><strong>Explanation:</strong></p>
<p><img alt="" src="assets/ec9169b84b1d414090574b24678224a0.jpeg" style="height: 180px; width: 180px;"/></p>
<ul>
<li>A horizontal cut after the first row gives sums <code>1 + 4 = 5</code> and <code>2 + 3 = 5</code>, which are equal. Thus, the answer is <code>true</code>.</li>
</ul>
</div>
<p><strong>Example 2:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">grid = [[1,2],[3,4]]</span></p>
<p><strong>Output:</strong> <span class="example-io">true</span></p>
<p><strong>Explanation:</strong></p>
<p><img alt="" src="assets/e89cddd0082343f3a75ad162c0392aab.png" style="height: 180px; width: 180px;"/></p>
<ul>
<li>A vertical cut after the first column gives sums <code>1 + 3 = 4</code> and <code>2 + 4 = 6</code>.</li>
<li>By discounting 2 from the right section (<code>6 - 2 = 4</code>), both sections have equal sums and remain connected. Thus, the answer is <code>true</code>.</li>
</ul>
</div>
<p><strong>Example 3:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">grid = [[1,2,4],[2,3,5]]</span></p>
<p><strong>Output:</strong> <span class="example-io">false</span></p>
<p><strong>Explanation:</strong></p>
<p><strong><img alt="" src="assets/e22694db07274b8da5146d1082ac14ad.png" style="height: 180px; width: 180px;"/></strong></p>
<ul>
<li>A horizontal cut after the first row gives <code>1 + 2 + 4 = 7</code> and <code>2 + 3 + 5 = 10</code>.</li>
<li>By discounting 3 from the bottom section (<code>10 - 3 = 7</code>), both sections have equal sums, but they do not remain connected as it splits the bottom section into two parts (<code>[2]</code> and <code>[5]</code>). Thus, the answer is <code>false</code>.</li>
</ul>
</div>
<p><strong>Example 4:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">grid = [[4,1,8],[3,2,6]]</span></p>
<p><strong>Output:</strong> <span class="example-io">false</span></p>
<p><strong>Explanation:</strong></p>
<p>No valid cut exists, so the answer is <code>false</code>.</p>
</div>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>1 &lt;= m == grid.length &lt;= 10<sup>5</sup></code></li>
<li><code>1 &lt;= n == grid[i].length &lt;= 10<sup>5</sup></code></li>
<li><code>2 &lt;= m * n &lt;= 10<sup>5</sup></code></li>
<li><code>1 &lt;= grid[i][j] &lt;= 10<sup>5</sup></code></li>
</ul>
</div>
