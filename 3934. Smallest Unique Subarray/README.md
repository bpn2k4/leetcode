
<h3>Smallest Unique Subarray</h3>
<div class="xg0bVG_html" data-qd-rendered-description="" data-track-load="description_content"><p>You are given an integer array <code>nums</code>.</p>
<p>Find the <strong>minimum </strong>length of a <span class="cursor-pointer relative text-dark-blue-s text-sm" data-keyword="subarray"><button aria-controls="radix-_r_u_" aria-expanded="false" aria-haspopup="dialog" class="" data-state="closed" type="button">subarray</button></span> that is <strong>not</strong> <strong>identical</strong> to any other <strong>subarray</strong> in <code>nums</code>.</p>
<p>Return an integer denoting the <strong>minimum possible length</strong> of such a <strong>subarray</strong>.</p>
<p>Two <strong>subarrays</strong> are considered identical if they have the same length and the same elements in corresponding positions.</p>
<p> </p>
<p><span class="float-right -my-0.5 ml-2 inline-flex select-none items-center" data-example-lang-controls=""><span class="inline-flex h-6 items-center rounded-sd-md bg-sd-muted p-0.5" data-example-lang-toggle="" role="group"><button aria-pressed="true" class="h-5 max-w-[10rem] truncate whitespace-nowrap rounded-sd-sm border px-2 text-xs font-normal leading-none border-sd-border bg-sd-background text-sd-foreground" type="button">Original</button><button aria-pressed="false" class="h-5 max-w-[10rem] truncate whitespace-nowrap rounded-sd-sm border px-2 text-xs font-normal leading-none border-transparent text-sd-muted-foreground hover:text-sd-foreground" type="button">Python3</button></span></span><strong>Example 1:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">nums = [3,3,3]</span></p>
<p><strong>Output:</strong> <span class="example-io">3</span></p>
<p><strong>Explanation:</strong></p>
<ul>
<li>Subarrays of length 1: <code>[3]</code> → appears 3 times</li>
<li>Subarrays of length 2: <code>[3, 3]</code> → appears 2 times</li>
<li>Subarrays of length 3: <code>[3, 3, 3]</code> → appears once</li>
</ul>
<p>The subarray <code>[3, 3, 3]</code> is unique, so the smallest unique subarray length is 3.</p>
</div>
<p><strong>Example 2:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">nums = [2,1,2,3,3]</span></p>
<p><strong>Output:</strong> <span class="example-io">1</span></p>
<p><strong>Explanation:</strong></p>
<p>Subarrays of length 1:</p>
<ul>
<li><code>[2]</code> → appears 2 times</li>
<li><code>[1]</code> → appears once</li>
<li><code>[3]</code> → appears 2 times</li>
</ul>
The subarray <code>[1]</code> is unique, so the smallest unique subarray length is 1.</div>
<p><strong>Example 3:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">nums = [1,1,2,2,1]</span></p>
<p><strong>Output:</strong> <span class="example-io">2</span></p>
<p><strong>Explanation:</strong></p>
<p>Subarrays of length 1:</p>
<ul>
<li><code>[1]</code> → appears 3 times</li>
<li><code>[2]</code> → appears 2 times</li>
</ul>
<p>Subarrays of length 2:</p>
<ul>
<li><code>[1, 1]</code> → appears once</li>
<li><code>[1, 2]</code> → appears once</li>
<li><code>[2, 2]</code> → appears once</li>
<li><code>[2, 1]</code> → appears once</li>
</ul>
There is at least one subarray of length 2 that is unique, so the smallest unique subarray length is 2.</div>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>1 &lt;= nums.length &lt;= 10<sup>5</sup></code></li>
<li><code>1 &lt;= nums[i] &lt;= 10<sup>5</sup></code></li>
</ul>
</div>
