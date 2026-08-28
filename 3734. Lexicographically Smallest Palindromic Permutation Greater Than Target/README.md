
<h3>Lexicographically Smallest Palindromic Permutation Greater Than Target</h3>
<div class="HTMLContent_html__0OZLp" data-qd-rendered-description="" data-track-load="description_content"><p>You are given two strings <code>s</code> and <code>target</code>, each of length <code>n</code>, consisting of lowercase English letters.</p>
<p>Return the <strong><span class="cursor-pointer relative text-dark-blue-s text-sm" data-keyword="lexicographically-smaller-string"><button aria-controls="radix-_r_1a_" aria-expanded="false" aria-haspopup="dialog" class="" data-state="closed" type="button">lexicographically smallest</button></span> string</strong> that is <strong>both</strong> a <strong><span class="cursor-pointer relative text-dark-blue-s text-sm" data-keyword="palindrome-string"><button aria-controls="radix-_r_1b_" aria-expanded="false" aria-haspopup="dialog" class="" data-state="closed" type="button">palindromic</button></span> <span class="cursor-pointer relative text-dark-blue-s text-sm" data-keyword="permutation"><button aria-controls="radix-_r_1c_" aria-expanded="false" aria-haspopup="dialog" class="" data-state="closed" type="button">permutation</button></span></strong> of <code>s</code> and <strong>strictly</strong> greater than <code>target</code>. If no such permutation exists, return an empty string.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">s = "baba", target = "abba"</span></p>
<p><strong>Output:</strong> <span class="example-io">"baab"</span></p>
<p><strong>Explanation:</strong></p>
<ul>
<li>The palindromic permutations of <code>s</code> (in lexicographical order) are <code>"abba"</code> and <code>"baab"</code>.</li>
<li>The lexicographically smallest permutation that is strictly greater than <code>target</code> is <code>"baab"</code>.</li>
</ul>
</div>
<p><strong>Example 2:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">s = "baba", target = "bbaa"</span></p>
<p><strong>Output:</strong> <span class="example-io">""</span></p>
<p><strong>Explanation:</strong></p>
<ul>
<li>The palindromic permutations of <code>s</code> (in lexicographical order) are <code>"abba"</code> and <code>"baab"</code>.</li>
<li>None of them is lexicographically strictly greater than <code>target</code>. Therefore, the answer is <code>""</code>.</li>
</ul>
</div>
<p><strong>Example 3:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">s = "abc", target = "abb"</span></p>
<p><strong>Output:</strong> <span class="example-io">""</span></p>
<p><strong>Explanation:</strong></p>
<p><code>s</code> has no palindromic permutations. Therefore, the answer is <code>""</code>.</p>
</div>
<p><strong>Example 4:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">s = "aac", target = "abb"</span></p>
<p><strong>Output:</strong> <span class="example-io">"aca"</span></p>
<p><strong>Explanation:</strong></p>
<ul>
<li>The only palindromic permutation of <code>s</code> is <code>"aca"</code>.</li>
<li><code>"aca"</code> is strictly greater than <code>target</code>. Therefore, the answer is <code>"aca"</code>.</li>
</ul>
</div>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>1 &lt;= n == s.length == target.length &lt;= 300</code></li>
<li><code>s</code> and <code>target</code> consist of only lowercase English letters.</li>
</ul>
</div>
