
<h3>Special Array II</h3>
<div><p>An array is considered <strong>special</strong> if every pair of its adjacent elements contains two numbers with different parity.</p>
<p>You are given an array of integer <code>nums</code> and a 2D integer matrix <code>queries</code>, where for <code>queries[i] = [from<sub>i</sub>, to<sub>i</sub>]</code> your task is to check that <span class="cursor-pointer relative text-dark-blue-s text-sm" data-keyword="subarray"><div class="popover-wrapper inline-block" data-headlessui-state=""><div><div aria-expanded="false" data-headlessui-state="" id="headlessui-popover-button-:rt:"><div>subarray</div></div><div style="position: fixed; z-index: 40; inset: 0px auto auto 0px; transform: translate(137px, 241px);"></div></div></div></span> <code>nums[from<sub>i</sub>..to<sub>i</sub>]</code> is <strong>special</strong> or not.</p>
<p>Return an array of booleans <code>answer</code> such that <code>answer[i]</code> is <code>true</code> if <code>nums[from<sub>i</sub>..to<sub>i</sub>]</code> is special.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">nums = [3,4,1,2,6], queries = [[0,4]]</span></p>
<p><strong>Output:</strong> <span class="example-io">[false]</span></p>
<p><strong>Explanation:</strong></p>
<p>The subarray is <code>[3,4,1,2,6]</code>. 2 and 6 are both even.</p>
</div>
<p><strong>Example 2:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">nums = [4,3,1,6], queries = [[0,2],[2,3]]</span></p>
<p><strong>Output:</strong> <span class="example-io">[false,true]</span></p>
<p><strong>Explanation:</strong></p>
<ol>
<li>The subarray is <code>[4,3,1]</code>. 3 and 1 are both odd. So the answer to this query is <code>false</code>.</li>
<li>The subarray is <code>[1,6]</code>. There is only one pair: <code>(1,6)</code> and it contains numbers with different parity. So the answer to this query is <code>true</code>.</li>
</ol>
</div>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>1 &lt;= nums.length &lt;= 10<sup>5</sup></code></li>
<li><code>1 &lt;= nums[i] &lt;= 10<sup>5</sup></code></li>
<li><code>1 &lt;= queries.length &lt;= 10<sup>5</sup></code></li>
<li><code>queries[i].length == 2</code></li>
<li><code>0 &lt;= queries[i][0] &lt;= queries[i][1] &lt;= nums.length - 1</code></li>
</ul>
</div>
