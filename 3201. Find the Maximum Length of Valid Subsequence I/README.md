
<h3>Find the Maximum Length of Valid Subsequence I</h3>
<div>You are given an integer array <code>nums</code>.
<p>A <span class="cursor-pointer relative text-dark-blue-s text-sm" data-keyword="subsequence-array"><button aria-controls="radix-:rs:" aria-expanded="false" aria-haspopup="dialog" class="" data-state="closed" type="button">subsequence</button></span> <code>sub</code> of <code>nums</code> with length <code>x</code> is called <strong>valid</strong> if it satisfies:</p>
<ul>
<li><code>(sub[0] + sub[1]) % 2 == (sub[1] + sub[2]) % 2 == ... == (sub[x - 2] + sub[x - 1]) % 2.</code></li>
</ul>
<p>Return the length of the <strong>longest</strong> <strong>valid</strong> subsequence of <code>nums</code>.</p>
<p>A <strong>subsequence</strong> is an array that can be derived from another array by deleting some or no elements without changing the order of the remaining elements.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">nums = [1,2,3,4]</span></p>
<p><strong>Output:</strong> <span class="example-io">4</span></p>
<p><strong>Explanation:</strong></p>
<p>The longest valid subsequence is <code>[1, 2, 3, 4]</code>.</p>
</div>
<p><strong>Example 2:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">nums = [1,2,1,1,2,1,2]</span></p>
<p><strong>Output:</strong> 6</p>
<p><strong>Explanation:</strong></p>
<p>The longest valid subsequence is <code>[1, 2, 1, 2, 1, 2]</code>.</p>
</div>
<p><strong>Example 3:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">nums = [1,3]</span></p>
<p><strong>Output:</strong> <span class="example-io">2</span></p>
<p><strong>Explanation:</strong></p>
<p>The longest valid subsequence is <code>[1, 3]</code>.</p>
</div>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>2 &lt;= nums.length &lt;= 2 * 10<sup>5</sup></code></li>
<li><code>1 &lt;= nums[i] &lt;= 10<sup>7</sup></code></li>
</ul>
</div>
