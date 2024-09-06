
<h3>Delete Nodes From Linked List Present in Array</h3>
<div><p>You are given an array of integers <code>nums</code> and the <code>head</code> of a linked list. Return the <code>head</code> of the modified linked list after <strong>removing</strong> all nodes from the linked list that have a value that exists in <code>nums</code>.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">nums = [1,2,3], head = [1,2,3,4,5]</span></p>
<p><strong>Output:</strong> <span class="example-io">[4,5]</span></p>
<p><strong>Explanation:</strong></p>
<p><strong><img alt="" src="assets/f3ff4a63ddd943188cffdf2df5f97525.png" style="width: 400px; height: 66px;"/></strong></p>
<p>Remove the nodes with values 1, 2, and 3.</p>
</div>
<p><strong>Example 2:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">nums = [1], head = [1,2,1,2,1,2]</span></p>
<p><strong>Output:</strong> <span class="example-io">[2,2,2]</span></p>
<p><strong>Explanation:</strong></p>
<p><img alt="" src="assets/7db12cde5bca427090a13bcc3529dbe7.png" style="height: 62px; width: 450px;"/></p>
<p>Remove the nodes with value 1.</p>
</div>
<p><strong>Example 3:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">nums = [5], head = [1,2,3,4]</span></p>
<p><strong>Output:</strong> <span class="example-io">[1,2,3,4]</span></p>
<p><strong>Explanation:</strong></p>
<p><strong><img alt="" src="assets/54c4c8c6558a42768e1d53628ebcf2ed.png" style="width: 400px; height: 83px;"/></strong></p>
<p>No node has value 5.</p>
</div>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>1 &lt;= nums.length &lt;= 10<sup>5</sup></code></li>
<li><code>1 &lt;= nums[i] &lt;= 10<sup>5</sup></code></li>
<li>All elements in <code>nums</code> are unique.</li>
<li>The number of nodes in the given list is in the range <code>[1, 10<sup>5</sup>]</code>.</li>
<li><code>1 &lt;= Node.val &lt;= 10<sup>5</sup></code></li>
<li>The input is generated such that there is at least one node in the linked list that has a value not present in <code>nums</code>.</li>
</ul>
</div>
