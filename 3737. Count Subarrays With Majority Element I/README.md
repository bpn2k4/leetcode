
<h3>Count Subarrays With Majority Element I</h3>
<div class="HTMLContent_html__0OZLp" data-track-load="description_content"><p>You are given an integer array <code>nums</code> and an integer <code>target</code>.</p>
<p>Return the number of <strong><span class="cursor-pointer relative text-dark-blue-s text-sm" data-keyword="subarray-nonempty"><button aria-controls="radix-_r_1v_" aria-expanded="false" aria-haspopup="dialog" class="" data-state="closed" type="button">subarrays</button></span></strong> of <code>nums</code> in which <code>target</code> is the <strong>majority element</strong>.</p>
<p>The <strong>majority element</strong> of a subarray is the element that appears <strong>strictly</strong> <strong>more than half</strong> of the times in that subarray.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">nums = [1,2,2,3], target = 2</span></p>
<p><strong>Output:</strong> <span class="example-io">5</span></p>
<p><strong>Explanation:</strong></p>
<p>Valid subarrays with <code>target = 2</code> as the majority element:</p>
<ul>
<li><code>nums[1..1] = [2]</code></li>
<li><code>nums[2..2] = [2]</code></li>
<li><code>nums[1..2] = [2,2]</code></li>
<li><code>nums[0..2] = [1,2,2]</code></li>
<li><code>nums[1..3] = [2,2,3]</code></li>
</ul>
<p>So there are 5 such subarrays.</p>
</div>
<p><strong>Example 2:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">nums = [1,1,1,1], target = 1</span></p>
<p><strong>Output:</strong> <span class="example-io">10</span></p>
<p><strong>Explanation: </strong></p>
<p><strong>​​​​​​​</strong>All 10 subarrays have 1 as the majority element.</p>
</div>
<p><strong>Example 3:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">nums = [1,2,3], target = 4</span></p>
<p><strong>Output:</strong> <span class="example-io">0</span></p>
<p><strong>Explanation:</strong></p>
<p><code>target = 4</code> does not appear in <code>nums</code> at all. Therefore, there cannot be any subarray where 4 is the majority element. Hence the answer is 0.</p>
</div>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>1 &lt;= nums.length &lt;= 1000</code></li>
<li><code>1 &lt;= nums[i] &lt;= 10<sup>​​​​​​​9</sup></code></li>
<li><code>1 &lt;= target &lt;= 10<sup>9</sup></code></li>
</ul>
</div>
