
<h3>Find the Lexicographically Smallest Valid Sequence</h3>
<div class="HTMLContent_html__0OZLp" data-qd-rendered-description="" data-track-load="description_content"><p>You are given two strings <code>word1</code> and <code>word2</code>.</p>
<p>A string <code>x</code> is called <strong>almost equal</strong> to <code>y</code> if you can change <strong>at most</strong> one character in <code>x</code> to make it <em>identical</em> to <code>y</code>.</p>
<p>A sequence of indices <code>seq</code> is called <strong>valid</strong> if:</p>
<ul>
<li>The indices are sorted in <strong>ascending</strong> order.</li>
<li><em>Concatenating</em> the characters at these indices in <code>word1</code> in <strong>the same</strong> order results in a string that is <strong>almost equal</strong> to <code>word2</code>.</li>
</ul>
<p>Return an array of size <code>word2.length</code> representing the <span class="cursor-pointer relative text-dark-blue-s text-sm" data-keyword="lexicographically-smaller-array"><button aria-controls="radix-_r_s_" aria-expanded="false" aria-haspopup="dialog" class="" data-state="closed" type="button">lexicographically smallest</button></span> <strong>valid</strong> sequence of indices. If no such sequence of indices exists, return an <strong>empty</strong> array.</p>
<p><strong>Note</strong> that the answer must represent the <em>lexicographically smallest array</em>, <strong>not</strong> the corresponding string formed by those indices.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">word1 = "vbcca", word2 = "abc"</span></p>
<p><strong>Output:</strong> <span class="example-io">[0,1,2]</span></p>
<p><strong>Explanation:</strong></p>
<p>The lexicographically smallest valid sequence of indices is <code>[0, 1, 2]</code>:</p>
<ul>
<li>Change <code>word1[0]</code> to <code>'a'</code>.</li>
<li><code>word1[1]</code> is already <code>'b'</code>.</li>
<li><code>word1[2]</code> is already <code>'c'</code>.</li>
</ul>
</div>
<p><strong>Example 2:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">word1 = "bacdc", word2 = "abc"</span></p>
<p><strong>Output:</strong> <span class="example-io">[1,2,4]</span></p>
<p><strong>Explanation:</strong></p>
<p>The lexicographically smallest valid sequence of indices is <code>[1, 2, 4]</code>:</p>
<ul>
<li><code>word1[1]</code> is already <code>'a'</code>.</li>
<li>Change <code>word1[2]</code> to <code>'b'</code>.</li>
<li><code>word1[4]</code> is already <code>'c'</code>.</li>
</ul>
</div>
<p><strong>Example 3:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">word1 = "aaaaaa", word2 = "aaabc"</span></p>
<p><strong>Output:</strong> <span class="example-io">[]</span></p>
<p><strong>Explanation:</strong></p>
<p>There is no valid sequence of indices.</p>
</div>
<p><strong>Example 4:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">word1 = "abc", word2 = "ab"</span></p>
<p><strong>Output:</strong> <span class="example-io">[0,1]</span></p>
</div>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>1 &lt;= word2.length &lt; word1.length &lt;= 3 * 10<sup>5</sup></code></li>
<li><code>word1</code> and <code>word2</code> consist only of lowercase English letters.</li>
</ul>
</div>
