
<h3>Longest Balanced Subarray II</h3>
<div><p>You are given an integer array <code>nums</code>.</p>
<p>A <strong><span class="cursor-pointer relative text-dark-blue-s text-sm" data-keyword="subarray-nonempty"><button aria-controls="radix-:r1n:" aria-expanded="false" aria-haspopup="dialog" class="" data-state="closed" type="button">subarray</button></span></strong> is called <strong>balanced</strong> if the number of <strong>distinct even</strong> numbers in the subarray is equal to the number of <strong>distinct odd</strong> numbers.</p>
<p>Return the length of the <strong>longest</strong> balanced subarray.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">nums = [2,5,4,3]</span></p>
<p><strong>Output:</strong> <span class="example-io">4</span></p>
<p><strong>Explanation:</strong></p>
<ul>
<li>The longest balanced subarray is <code>[2, 5, 4, 3]</code>.</li>
<li>It has 2 distinct even numbers <code>[2, 4]</code> and 2 distinct odd numbers <code>[5, 3]</code>. Thus, the answer is 4.</li>
</ul>
</div>
<p><strong>Example 2:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">nums = [3,2,2,5,4]</span></p>
<p><strong>Output:</strong> <span class="example-io">5</span></p>
<p><strong>Explanation:</strong></p>
<ul>
<li>The longest balanced subarray is <code>[3, 2, 2, 5, 4]</code>.</li>
<li>It has 2 distinct even numbers <code>[2, 4]</code> and 2 distinct odd numbers <code>[3, 5]</code>. Thus, the answer is 5.</li>
</ul>
</div>
<p><strong>Example 3:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">nums = [1,2,3,2]</span></p>
<p><strong>Output:</strong> <span class="example-io">3</span></p>
<p><strong>Explanation:</strong></p>
<ul>
<li>The longest balanced subarray is <code>[2, 3, 2]</code>.</li>
<li>It has 1 distinct even number <code>[2]</code> and 1 distinct odd number <code>[3]</code>. Thus, the answer is 3.</li>
</ul>
</div>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>1 &lt;= nums.length &lt;= 10<sup>5</sup></code></li>
<li><code>1 &lt;= nums[i] &lt;= 10<sup>5</sup></code></li>
</ul>
</div>
