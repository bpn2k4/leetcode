
<h3>Longest Subsequence With Non-Zero Bitwise XOR</h3>
<div class="HTMLContent_html__0OZLp" data-qd-rendered-description="" data-track-load="description_content"><p>You are given an integer array <code>nums</code>.</p>
<p>Return the length of the <strong>longest <span class="cursor-pointer relative text-dark-blue-s text-sm" data-keyword="subsequence-array-nonempty"><button aria-controls="radix-_r_s_" aria-expanded="false" aria-haspopup="dialog" class="" data-state="closed" type="button">subsequence</button></span></strong> in <code>nums</code> whose bitwise <strong>XOR</strong> is <strong>non-zero</strong>. If no such <strong>subsequence</strong> exists, return 0.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">nums = [1,2,3]</span></p>
<p><strong>Output:</strong> <span class="example-io">2</span></p>
<p><strong>Explanation:</strong></p>
<p>One longest subsequence is <code>[2, 3]</code>. The bitwise XOR is computed as <code>2 XOR 3 = 1</code>, which is non-zero.</p>
</div>
<p><strong>Example 2:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">nums = [2,3,4]</span></p>
<p><strong>Output:</strong> <span class="example-io">3</span></p>
<p><strong>Explanation:</strong></p>
<p>The longest subsequence is <code>[2, 3, 4]</code>. The bitwise XOR is computed as <code>2 XOR 3 XOR 4 = 5</code>, which is non-zero.</p>
</div>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>1 &lt;= nums.length &lt;= 10<sup>5</sup></code></li>
<li><code>0 &lt;= nums[i] &lt;= 10<sup>9</sup></code></li>
</ul>
</div>
