
<h3>Count Non-Decreasing Subarrays After K Operations</h3>
<div class="xg0bVG_html" data-qd-rendered-description="" data-track-load="description_content"><p>You are given an array <code>nums</code> of <code>n</code> integers and an integer <code>k</code>.</p>
<p>For each subarray of <code>nums</code>, you can apply <strong>up to</strong> <code>k</code> operations on it. In each operation, you increment any element of the subarray by 1.</p>
<p><strong>Note</strong> that each subarray is considered independently, meaning changes made to one subarray do not persist to another.</p>
<p>Return the number of subarrays that you can make <strong>non-decreasing</strong> ​​​​​after performing at most <code>k</code> operations.</p>
<p>An array is said to be <strong>non-decreasing</strong> if each element is greater than or equal to its previous element, if it exists.</p>
<p> </p>
<p><span class="float-right -my-0.5 ml-2 inline-flex select-none items-center" data-example-lang-controls=""><span class="inline-flex h-6 items-center rounded-sd-md bg-sd-muted p-0.5" data-example-lang-toggle="" role="group"><button aria-pressed="true" class="h-5 max-w-[10rem] truncate whitespace-nowrap rounded-sd-sm border px-2 text-xs font-normal leading-none border-sd-border bg-sd-background text-sd-foreground" type="button">Original</button><button aria-pressed="false" class="h-5 max-w-[10rem] truncate whitespace-nowrap rounded-sd-sm border px-2 text-xs font-normal leading-none border-transparent text-sd-muted-foreground hover:text-sd-foreground" type="button">Python3</button></span></span><strong>Example 1:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">nums = [6,3,1,2,4,4], k = 7</span></p>
<p><strong>Output:</strong> <span class="example-io">17</span></p>
<p><strong>Explanation:</strong></p>
<p>Out of all 21 possible subarrays of <code>nums</code>, only the subarrays <code>[6, 3, 1]</code>, <code>[6, 3, 1, 2]</code>, <code>[6, 3, 1, 2, 4]</code> and <code>[6, 3, 1, 2, 4, 4]</code> cannot be made non-decreasing after applying up to k = 7 operations. Thus, the number of non-decreasing subarrays is <code>21 - 4 = 17</code>.</p>
</div>
<p><strong>Example 2:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">nums = [6,3,1,3,6], k = 4</span></p>
<p><strong>Output:</strong> <span class="example-io">12</span></p>
<p><strong>Explanation:</strong></p>
<p>The subarray <code>[3, 1, 3, 6]</code> along with all subarrays of <code>nums</code> with three or fewer elements, except <code>[6, 3, 1]</code>, can be made non-decreasing after <code>k</code> operations. There are 5 subarrays of a single element, 4 subarrays of two elements, and 2 subarrays of three elements except <code>[6, 3, 1]</code>, so there are <code>1 + 5 + 4 + 2 = 12</code> subarrays that can be made non-decreasing.</p>
</div>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>1 &lt;= nums.length &lt;= 10<sup>5</sup></code></li>
<li><code>1 &lt;= nums[i] &lt;= 10<sup>9</sup></code></li>
<li><code>1 &lt;= k &lt;= 10<sup>9</sup></code></li>
</ul>
</div>
