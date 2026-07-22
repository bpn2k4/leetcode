
<h3>Maximize Active Section with Trade II</h3>
<div class="HTMLContent_html__0OZLp" data-track-load="description_content"><p>You are given a binary string <code>s</code> of length <code>n</code>, where:</p>
<ul>
<li><code>'1'</code> represents an <strong>active</strong> section.</li>
<li><code>'0'</code> represents an <strong>inactive</strong> section.</li>
</ul>
<p>You can perform <strong>at most one trade</strong> to maximize the number of active sections in <code>s</code>. In a trade, you:</p>
<ul>
<li>Convert a contiguous block of <code>'1'</code>s that is surrounded by <code>'0'</code>s to all <code>'0'</code>s.</li>
<li>Afterward, convert a contiguous block of <code>'0'</code>s that is surrounded by <code>'1'</code>s to all <code>'1'</code>s.</li>
</ul>
<p>Additionally, you are given a <strong>2D array</strong> <code>queries</code>, where <code>queries[i] = [l<sub>i</sub>, r<sub>i</sub>]</code> represents a <span class="cursor-pointer relative text-dark-blue-s text-sm" data-keyword="substring-nonempty"><button aria-controls="radix-_r_21_" aria-expanded="false" aria-haspopup="dialog" class="" data-state="closed" type="button">substring</button></span> <code>s[l<sub>i</sub>...r<sub>i</sub>]</code>.</p>
<p>For each query, determine the <strong>maximum</strong> possible number of active sections in <code>s</code> after making the optimal trade on the substring <code>s[l<sub>i</sub>...r<sub>i</sub>]</code>.</p>
<p>Return an array <code>answer</code>, where <code>answer[i]</code> is the result for <code>queries[i]</code>.</p>
<p><strong>Note</strong></p>
<ul>
<li>For each query, treat <code>s[l<sub>i</sub>...r<sub>i</sub>]</code> as if it is <strong>augmented</strong> with a <code>'1'</code> at both ends, forming <code>t = '1' + s[l<sub>i</sub>...r<sub>i</sub>] + '1'</code>. The augmented <code>'1'</code>s <strong>do not</strong> contribute to the final count.</li>
<li>The queries are independent of each other.</li>
</ul>
<p> </p>
<p><strong>Example 1:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">s = "01", queries = [[0,1]]</span></p>
<p><strong>Output:</strong> <span class="example-io">[1]</span></p>
<p><strong>Explanation:</strong></p>
<p>Because there is no block of <code>'1'</code>s surrounded by <code>'0'</code>s, no valid trade is possible. The maximum number of active sections is 1.</p>
</div>
<p><strong>Example 2:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">s = "0100", queries = [[0,3],[0,2],[1,3],[2,3]]</span></p>
<p><strong>Output:</strong> <span class="example-io">[4,3,1,1]</span></p>
<p><strong>Explanation:</strong></p>
<ul>
<li>
<p>Query <code>[0, 3]</code> → Substring <code>"0100"</code> → Augmented to <code>"101001"</code><br/>
	Choose <code>"0100"</code>, convert <code>"0100"</code> → <code>"0000"</code> → <code>"1111"</code>.<br/>
	The final string without augmentation is <code>"1111"</code>. The maximum number of active sections is 4.</p>
</li>
<li>
<p>Query <code>[0, 2]</code> → Substring <code>"010"</code> → Augmented to <code>"10101"</code><br/>
	Choose <code>"010"</code>, convert <code>"010"</code> → <code>"000"</code> → <code>"111"</code>.<br/>
	The final string without augmentation is <code>"1110"</code>. The maximum number of active sections is 3.</p>
</li>
<li>
<p>Query <code>[1, 3]</code> → Substring <code>"100"</code> → Augmented to <code>"11001"</code><br/>
	Because there is no block of <code>'1'</code>s surrounded by <code>'0'</code>s, no valid trade is possible. The maximum number of active sections is 1.</p>
</li>
<li>
<p>Query <code>[2, 3]</code> → Substring <code>"00"</code> → Augmented to <code>"1001"</code><br/>
	Because there is no block of <code>'1'</code>s surrounded by <code>'0'</code>s, no valid trade is possible. The maximum number of active sections is 1.</p>
</li>
</ul>
</div>
<p><strong>Example 3:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">s = "1000100", queries = [[1,5],[0,6],[0,4]]</span></p>
<p><strong>Output:</strong> <span class="example-io">[6,7,2]</span></p>
<p><strong>Explanation:</strong></p>
<ul>
<li data-end="383" data-start="217">
<p data-end="383" data-start="219">Query <code>[1, 5]</code> → Substring <code data-end="255" data-start="246">"00010"</code> → Augmented to <code data-end="282" data-start="271">"1000101"</code><br data-end="285" data-start="282"/>
	Choose <code data-end="303" data-start="294">"00010"</code>, convert <code data-end="322" data-start="313">"00010"</code> → <code data-end="322" data-start="313">"00000"</code> → <code data-end="334" data-start="325">"11111"</code>.<br/>
	The final string without augmentation is <code data-end="404" data-start="396">"1111110"</code>. The maximum number of active sections is 6.</p>
</li>
<li data-end="561" data-start="385">
<p data-end="561" data-start="387">Query <code>[0, 6]</code> → Substring <code data-end="425" data-start="414">"1000100"</code> → Augmented to <code data-end="454" data-start="441">"110001001"</code><br data-end="457" data-start="454"/>
	Choose <code data-end="477" data-start="466">"000100"</code>, convert <code data-end="498" data-start="487">"000100"</code> → <code data-end="498" data-start="487">"000000"</code> → <code data-end="512" data-start="501">"111111"</code>.<br/>
	The final string without augmentation is <code data-end="404" data-start="396">"1111111"</code>. The maximum number of active sections is 7.</p>
</li>
<li data-end="741" data-start="563">
<p data-end="741" data-start="565">Query <code>[0, 4]</code> → Substring <code data-end="601" data-start="592">"10001"</code> → Augmented to <code data-end="627" data-start="617">"1100011"</code><br data-end="630" data-start="627"/>
	Because there is no block of <code>'1'</code>s surrounded by <code>'0'</code>s, no valid trade is possible. The maximum number of active sections is 2.</p>
</li>
</ul>
</div>
<p><strong>Example 4:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">s = "01010", queries = [[0,3],[1,4],[1,3]]</span></p>
<p><strong>Output:</strong> <span class="example-io">[4,4,2]</span></p>
<p><strong>Explanation:</strong></p>
<ul>
<li>
<p>Query <code>[0, 3]</code> → Substring <code>"0101"</code> → Augmented to <code>"101011"</code><br/>
	Choose <code>"010"</code>, convert <code>"010"</code> → <code>"000"</code> → <code>"111"</code>.<br/>
	The final string without augmentation is <code>"11110"</code>. The maximum number of active sections is 4.</p>
</li>
<li>
<p>Query <code>[1, 4]</code> → Substring <code>"1010"</code> → Augmented to <code>"110101"</code><br/>
	Choose <code>"010"</code>, convert <code>"010"</code> → <code>"000"</code> → <code>"111"</code>.<br/>
	The final string without augmentation is <code>"01111"</code>. The maximum number of active sections is 4.</p>
</li>
<li>
<p>Query <code>[1, 3]</code> → Substring <code>"101"</code> → Augmented to <code>"11011"</code><br/>
	Because there is no block of <code>'1'</code>s surrounded by <code>'0'</code>s, no valid trade is possible. The maximum number of active sections is 2.</p>
</li>
</ul>
</div>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>1 &lt;= n == s.length &lt;= 10<sup>5</sup></code></li>
<li><code>1 &lt;= queries.length &lt;= 10<sup>5</sup></code></li>
<li><code>s[i]</code> is either <code>'0'</code> or <code>'1'</code>.</li>
<li><code>queries[i] = [l<sub>i</sub>, r<sub>i</sub>]</code></li>
<li><code>0 &lt;= l<sub>i</sub> &lt;= r<sub>i</sub> &lt; n</code></li>
</ul>
</div>
