
<h3>Longest Strictly Increasing or Strictly Decreasing Subarray</h3>
<div><p>You are given an array of integers <code>nums</code>. Return <em>the length of the <strong>longest</strong> <span class="cursor-pointer relative text-dark-blue-s text-sm" data-keyword="subarray-nonempty"><div class="popover-wrapper inline-block" data-headlessui-state=""><div><div aria-expanded="false" data-headlessui-state="" id="headlessui-popover-button-:rt:"><div>subarray</div></div><div style="position: fixed; z-index: 40; inset: 0px auto auto 0px; transform: translate(504px, 183px);"></div></div></div></span> of </em><code>nums</code><em> which is either <strong><span class="cursor-pointer relative text-dark-blue-s text-sm" data-keyword="strictly-increasing-array"><div class="popover-wrapper inline-block" data-headlessui-state=""><div><div aria-expanded="false" data-headlessui-state="" id="headlessui-popover-button-:rv:"><div>strictly increasing</div></div><div style="position: fixed; z-index: 40; inset: 0px auto auto 0px; transform: translate(737px, 183px);"></div></div></div></span></strong> or <strong><span class="cursor-pointer relative text-dark-blue-s text-sm" data-keyword="strictly-decreasing-array"><div class="popover-wrapper inline-block" data-headlessui-state=""><div><div aria-expanded="false" data-headlessui-state="" id="headlessui-popover-button-:r11:"><div>strictly decreasing</div></div><div style="position: fixed; z-index: 40; inset: 0px auto auto 0px; transform: translate(102px, 204px);"></div></div></div></span></strong></em>.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">nums = [1,4,3,3,2]</span></p>
<p><strong>Output:</strong> <span class="example-io">2</span></p>
<p><strong>Explanation:</strong></p>
<p>The strictly increasing subarrays of <code>nums</code> are <code>[1]</code>, <code>[2]</code>, <code>[3]</code>, <code>[3]</code>, <code>[4]</code>, and <code>[1,4]</code>.</p>
<p>The strictly decreasing subarrays of <code>nums</code> are <code>[1]</code>, <code>[2]</code>, <code>[3]</code>, <code>[3]</code>, <code>[4]</code>, <code>[3,2]</code>, and <code>[4,3]</code>.</p>
<p>Hence, we return <code>2</code>.</p>
</div>
<p><strong>Example 2:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">nums = [3,3,3,3]</span></p>
<p><strong>Output:</strong> <span class="example-io">1</span></p>
<p><strong>Explanation:</strong></p>
<p>The strictly increasing subarrays of <code>nums</code> are <code>[3]</code>, <code>[3]</code>, <code>[3]</code>, and <code>[3]</code>.</p>
<p>The strictly decreasing subarrays of <code>nums</code> are <code>[3]</code>, <code>[3]</code>, <code>[3]</code>, and <code>[3]</code>.</p>
<p>Hence, we return <code>1</code>.</p>
</div>
<p><strong>Example 3:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">nums = [3,2,1]</span></p>
<p><strong>Output:</strong> <span class="example-io">3</span></p>
<p><strong>Explanation:</strong></p>
<p>The strictly increasing subarrays of <code>nums</code> are <code>[3]</code>, <code>[2]</code>, and <code>[1]</code>.</p>
<p>The strictly decreasing subarrays of <code>nums</code> are <code>[3]</code>, <code>[2]</code>, <code>[1]</code>, <code>[3,2]</code>, <code>[2,1]</code>, and <code>[3,2,1]</code>.</p>
<p>Hence, we return <code>3</code>.</p>
</div>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>1 &lt;= nums.length &lt;= 50</code></li>
<li><code>1 &lt;= nums[i] &lt;= 50</code></li>
</ul>
</div>
