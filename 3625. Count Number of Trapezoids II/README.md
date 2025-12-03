
<h3>Count Number of Trapezoids II</h3>
<div><p data-end="189" data-start="146">You are given a 2D integer array <code>points</code> where <code>points[i] = [x<sub>i</sub>, y<sub>i</sub>]</code> represents the coordinates of the <code>i<sup>th</sup></code> point on the Cartesian plane.</p>
<p data-end="189" data-start="146">Return <em data-end="330" data-start="297">the number of unique </em><em>trapezoids</em> that can be formed by choosing any four distinct points from <code>points</code>.</p>
<p data-end="579" data-start="405">A<b> </b><strong>trapezoid</strong> is a convex quadrilateral with <strong data-end="496" data-start="475">at least one pair</strong> of parallel sides. Two lines are parallel if and only if they have the same slope.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">points = [[-3,2],[3,0],[2,3],[3,2],[2,-3]]</span></p>
<p><strong>Output:</strong> <span class="example-io">2</span></p>
<p><strong>Explanation:</strong></p>
<p><img alt="" src="assets/2b30b03a10e7424f9f3b39f030f6b55b.png" style="width: 250px; height: 250px;"/> <img alt="" src="assets/dd3c3603d8124f39b370a694efad74f8.png" style="width: 250px; height: 250px;"/></p>
<p>There are two distinct ways to pick four points that form a trapezoid:</p>
<ul>
<li>The points <code>[-3,2], [2,3], [3,2], [2,-3]</code> form one trapezoid.</li>
<li>The points <code>[2,3], [3,2], [3,0], [2,-3]</code> form another trapezoid.</li>
</ul>
</div>
<p><strong>Example 2:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">points = [[0,0],[1,0],[0,1],[2,1]]</span></p>
<p><strong>Output:</strong> <span class="example-io">1</span></p>
<p><strong>Explanation:</strong></p>
<p><img alt="" src="assets/c0655ad04afa4fc3badcfe58ca876321.png" style="width: 250px; height: 250px;"/></p>
<p>There is only one trapezoid which can be formed.</p>
</div>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>4 &lt;= points.length &lt;= 500</code></li>
<li><code>–1000 &lt;= x<sub>i</sub>, y<sub>i</sub> &lt;= 1000</code></li>
<li>All points are pairwise distinct.</li>
</ul>
</div>
