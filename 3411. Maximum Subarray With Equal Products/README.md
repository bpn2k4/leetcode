
<h3>Maximum Subarray With Equal Products</h3>
<div class="xg0bVG_html" data-qd-rendered-description="" data-track-load="description_content"><p>You are given an array of <strong>positive</strong> integers <code>nums</code>.</p>
<p>An array <code>arr</code> is called <strong>product equivalent</strong> if <code>prod(arr) == lcm(arr) * gcd(arr)</code>, where:</p>
<ul>
<li><code>prod(arr)</code> is the product of all elements of <code>arr</code>.</li>
<li><code>gcd(arr)</code> is the <span class="cursor-pointer relative text-dark-blue-s text-sm" data-keyword="gcd-function"><button aria-controls="radix-_r_10_" aria-expanded="false" aria-haspopup="dialog" class="" data-state="closed" type="button">GCD</button></span> of all elements of <code>arr</code>.</li>
<li><code>lcm(arr)</code> is the <span class="cursor-pointer relative text-dark-blue-s text-sm" data-keyword="lcm-function"><button aria-controls="radix-_r_11_" aria-expanded="false" aria-haspopup="dialog" class="" data-state="closed" type="button">LCM</button></span> of all elements of <code>arr</code>.</li>
</ul>
<p>Return the length of the <strong>longest</strong> <strong>product equivalent</strong> <span class="cursor-pointer relative text-dark-blue-s text-sm" data-keyword="subarray-nonempty"><button aria-controls="radix-_r_12_" aria-expanded="false" aria-haspopup="dialog" class="" data-state="closed" type="button">subarray</button></span> of <code>nums</code>.</p>
<p> </p>
<p><span class="float-right -my-0.5 ml-2 inline-flex select-none items-center" data-example-lang-controls=""><span class="inline-flex h-6 items-center rounded-sd-md bg-sd-muted p-0.5" data-example-lang-toggle="" role="group"><button aria-pressed="true" class="h-5 max-w-[10rem] truncate whitespace-nowrap rounded-sd-sm border px-2 text-xs font-normal leading-none border-sd-border bg-sd-background text-sd-foreground" type="button">Original</button><button aria-pressed="false" class="h-5 max-w-[10rem] truncate whitespace-nowrap rounded-sd-sm border px-2 text-xs font-normal leading-none border-transparent text-sd-muted-foreground hover:text-sd-foreground" type="button">Python3</button></span></span><strong>Example 1:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">nums = [1,2,1,2,1,1,1]</span></p>
<p><strong>Output:</strong> <span class="example-io">5</span></p>
<p><strong>Explanation:</strong> </p>
<p>The longest product equivalent subarray is <code>[1, 2, 1, 1, 1]</code>, where <code>prod([1, 2, 1, 1, 1]) = 2</code>, <code>gcd([1, 2, 1, 1, 1]) = 1</code>, and <code>lcm([1, 2, 1, 1, 1]) = 2</code>.</p>
</div>
<p><strong>Example 2:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">nums = [2,3,4,5,6]</span></p>
<p><strong>Output:</strong> <span class="example-io">3</span></p>
<p><strong>Explanation:</strong> </p>
<p>The longest product equivalent subarray is <code>[3, 4, 5].</code></p>
</div>
<p><strong>Example 3:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">nums = [1,2,3,1,4,5,1]</span></p>
<p><strong>Output:</strong> <span class="example-io">5</span></p>
</div>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>2 &lt;= nums.length &lt;= 100</code></li>
<li><code>1 &lt;= nums[i] &lt;= 10</code></li>
</ul>
</div>
