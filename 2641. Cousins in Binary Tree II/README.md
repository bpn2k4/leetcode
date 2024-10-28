
<h3>Cousins in Binary Tree II</h3>
<div><p>Given the <code>root</code> of a binary tree, replace the value of each node in the tree with the <strong>sum of all its cousins' values</strong>.</p>
<p>Two nodes of a binary tree are <strong>cousins</strong> if they have the same depth with different parents.</p>
<p>Return <em>the </em><code>root</code><em> of the modified tree</em>.</p>
<p><strong>Note</strong> that the depth of a node is the number of edges in the path from the root node to it.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<img alt="" src="assets/e9fdcd394f0b4bafabc1eb34924742c3.png" style="width: 571px; height: 151px;"/>
<pre><strong>Input:</strong> root = [5,4,9,1,10,null,7]
<strong>Output:</strong> [0,0,0,7,7,null,11]
<strong>Explanation:</strong> The diagram above shows the initial binary tree and the binary tree after changing the value of each node.
- Node with value 5 does not have any cousins so its sum is 0.
- Node with value 4 does not have any cousins so its sum is 0.
- Node with value 9 does not have any cousins so its sum is 0.
- Node with value 1 has a cousin with value 7 so its sum is 7.
- Node with value 10 has a cousin with value 7 so its sum is 7.
- Node with value 7 has cousins with values 1 and 10 so its sum is 11.
</pre>
<p><strong>Example 2:</strong></p>
<img alt="" src="assets/5731c7caabe7471bbdb1940ec5a29ecd.png" style="width: 481px; height: 91px;"/>
<pre><strong>Input:</strong> root = [3,1,2]
<strong>Output:</strong> [0,0,0]
<strong>Explanation:</strong> The diagram above shows the initial binary tree and the binary tree after changing the value of each node.
- Node with value 3 does not have any cousins so its sum is 0.
- Node with value 1 does not have any cousins so its sum is 0.
- Node with value 2 does not have any cousins so its sum is 0.
</pre>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li>The number of nodes in the tree is in the range <code>[1, 10<sup>5</sup>]</code>.</li>
<li><code>1 &lt;= Node.val &lt;= 10<sup>4</sup></code></li>
</ul>
</div>