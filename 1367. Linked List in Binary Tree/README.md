
<h3>Linked List in Binary Tree</h3>
<div><p>Given a binary tree <code>root</code> and a linked list with <code>head</code> as the first node. </p>
<p>Return True if all the elements in the linked list starting from the <code>head</code> correspond to some <em>downward path</em> connected in the binary tree otherwise return False.</p>
<p>In this context downward path means a path that starts at some node and goes downwards.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<p><strong><img alt="" src="assets/53428777710b40a6943fe40a61f2e35d.png" style="width: 220px; height: 280px;"/></strong></p>
<pre><strong>Input:</strong> head = [4,2,8], root = [1,4,4,null,2,2,null,1,null,6,8,null,null,null,null,1,3]
<strong>Output:</strong> true
<strong>Explanation:</strong> Nodes in blue form a subpath in the binary Tree.  
</pre>
<p><strong>Example 2:</strong></p>
<p><strong><img alt="" src="assets/0b6b8b9619da4d1581c5c54f648ee1f3.png" style="width: 220px; height: 280px;"/></strong></p>
<pre><strong>Input:</strong> head = [1,4,2,6], root = [1,4,4,null,2,2,null,1,null,6,8,null,null,null,null,1,3]
<strong>Output:</strong> true
</pre>
<p><strong>Example 3:</strong></p>
<pre><strong>Input:</strong> head = [1,4,2,6,8], root = [1,4,4,null,2,2,null,1,null,6,8,null,null,null,null,1,3]
<strong>Output:</strong> false
<strong>Explanation:</strong> There is no path in the binary tree that contains all the elements of the linked list from <code>head</code>.
</pre>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li>The number of nodes in the tree will be in the range <code>[1, 2500]</code>.</li>
<li>The number of nodes in the list will be in the range <code>[1, 100]</code>.</li>
<li><code>1 &lt;= Node.val &lt;= 100</code> for each node in the linked list and binary tree.</li>
</ul>
</div>
