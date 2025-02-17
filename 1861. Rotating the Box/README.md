
<h3>Rotating the Box</h3>
<div><p>You are given an <code>m x n</code> matrix of characters <code>box</code> representing a side-view of a box. Each cell of the box is one of the following:</p>
<ul>
<li>A stone <code>'#'</code></li>
<li>A stationary obstacle <code>'*'</code></li>
<li>Empty <code>'.'</code></li>
</ul>
<p>The box is rotated <strong>90 degrees clockwise</strong>, causing some of the stones to fall due to gravity. Each stone falls down until it lands on an obstacle, another stone, or the bottom of the box. Gravity <strong>does not</strong> affect the obstacles' positions, and the inertia from the box's rotation <strong>does not </strong>affect the stones' horizontal positions.</p>
<p>It is <strong>guaranteed</strong> that each stone in <code>box</code> rests on an obstacle, another stone, or the bottom of the box.</p>
<p>Return <em>an </em><code>n x m</code><em> matrix representing the box after the rotation described above</em>.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<p><img alt="" src="assets/71788c0f744f4ab69b64e0090468bdc0.png" style="width: 300px; height: 150px;"/></p>
<pre><strong>Input:</strong> box = [["#",".","#"]]
<strong>Output:</strong> [["."],
         ["#"],
         ["#"]]
</pre>
<p><strong>Example 2:</strong></p>
<p><img alt="" src="assets/5613633cf3b04ecfbf526e7311849b6f.png" style="width: 375px; height: 195px;"/></p>
<pre><strong>Input:</strong> box = [["#",".","*","."],
              ["#","#","*","."]]
<strong>Output:</strong> [["#","."],
         ["#","#"],
         ["*","*"],
         [".","."]]
</pre>
<p><strong>Example 3:</strong></p>
<p><img alt="" src="assets/3f3fc8679dda4668a40ac1b941a148dd.png" style="width: 400px; height: 218px;"/></p>
<pre><strong>Input:</strong> box = [["#","#","*",".","*","."],
              ["#","#","#","*",".","."],
              ["#","#","#",".","#","."]]
<strong>Output:</strong> [[".","#","#"],
         [".","#","#"],
         ["#","#","*"],
         ["#","*","."],
         ["#",".","*"],
         ["#",".","."]]
</pre>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>m == box.length</code></li>
<li><code>n == box[i].length</code></li>
<li><code>1 &lt;= m, n &lt;= 500</code></li>
<li><code>box[i][j]</code> is either <code>'#'</code>, <code>'*'</code>, or <code>'.'</code>.</li>
</ul></div>
