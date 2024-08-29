
<h3>Path with Maximum Probability</h3>
<div><p>You are given an undirected weighted graph of <code>n</code> nodes (0-indexed), represented by an edge list where <code>edges[i] = [a, b]</code> is an undirected edge connecting the nodes <code>a</code> and <code>b</code> with a probability of success of traversing that edge <code>succProb[i]</code>.</p>
<p>Given two nodes <code>start</code> and <code>end</code>, find the path with the maximum probability of success to go from <code>start</code> to <code>end</code> and return its success probability.</p>
<p>If there is no path from <code>start</code> to <code>end</code>, <strong>return 0</strong>. Your answer will be accepted if it differs from the correct answer by at most <strong>1e-5</strong>.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<p><strong><img alt="" src="assets/a61a40711f904bfa8c2fc45426ec29a4.png" style="width: 187px; height: 186px;"/></strong></p>
<pre><strong>Input:</strong> n = 3, edges = [[0,1],[1,2],[0,2]], succProb = [0.5,0.5,0.2], start = 0, end = 2
<strong>Output:</strong> 0.25000
<strong>Explanation:</strong> There are two paths from start to end, one having a probability of success = 0.2 and the other has 0.5 * 0.5 = 0.25.
</pre>
<p><strong>Example 2:</strong></p>
<p><strong><img alt="" src="assets/da00cff5fe5f4f32bf6fa0a0770de193.png" style="width: 189px; height: 186px;"/></strong></p>
<pre><strong>Input:</strong> n = 3, edges = [[0,1],[1,2],[0,2]], succProb = [0.5,0.5,0.3], start = 0, end = 2
<strong>Output:</strong> 0.30000
</pre>
<p><strong>Example 3:</strong></p>
<p><strong><img alt="" src="assets/edb785b0c6374c3385b37103cf9af8be.png" style="width: 215px; height: 191px;"/></strong></p>
<pre><strong>Input:</strong> n = 3, edges = [[0,1]], succProb = [0.5], start = 0, end = 2
<strong>Output:</strong> 0.00000
<strong>Explanation:</strong> There is no path between 0 and 2.
</pre>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>2 &lt;= n &lt;= 10^4</code></li>
<li><code>0 &lt;= start, end &lt; n</code></li>
<li><code>start != end</code></li>
<li><code>0 &lt;= a, b &lt; n</code></li>
<li><code>a != b</code></li>
<li><code>0 &lt;= succProb.length == edges.length &lt;= 2*10^4</code></li>
<li><code>0 &lt;= succProb[i] &lt;= 1</code></li>
<li>There is at most one edge between every two nodes.</li>
</ul>
</div>