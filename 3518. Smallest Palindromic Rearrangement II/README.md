
<h3>Smallest Palindromic Rearrangement II</h3>
<div class="HTMLContent_html__0OZLp" data-track-load="description_content"><p data-end="332" data-start="99">You are given a <strong><span class="cursor-pointer relative text-dark-blue-s text-sm" data-keyword="palindrome-string"><button aria-controls="radix-_r_23_" aria-expanded="false" aria-haspopup="dialog" class="" data-state="closed" type="button">palindromic</button></span></strong> string <code>s</code> and an integer <code>k</code>.</p>
<p>Return the <strong>k-th</strong> <strong><span class="cursor-pointer relative text-dark-blue-s text-sm" data-keyword="lexicographically-smaller-string"><button aria-controls="radix-_r_24_" aria-expanded="false" aria-haspopup="dialog" class="" data-state="closed" type="button">lexicographically smallest</button></span></strong> palindromic <span class="cursor-pointer relative text-dark-blue-s text-sm" data-keyword="permutation-string"><button aria-controls="radix-_r_25_" aria-expanded="false" aria-haspopup="dialog" class="" data-state="closed" type="button">permutation</button></span> of <code>s</code>. If there are fewer than <code>k</code> distinct palindromic permutations, return an empty string.</p>
<p><strong>Note:</strong> Different rearrangements that yield the same palindromic string are considered identical and are counted once.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">s = "abba", k = 2</span></p>
<p><strong>Output:</strong> <span class="example-io">"baab"</span></p>
<p><strong>Explanation:</strong></p>
<ul>
<li>The two distinct palindromic rearrangements of <code>"abba"</code> are <code>"abba"</code> and <code>"baab"</code>.</li>
<li>Lexicographically, <code>"abba"</code> comes before <code>"baab"</code>. Since <code>k = 2</code>, the output is <code>"baab"</code>.</li>
</ul>
</div>
<p><strong>Example 2:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">s = "aa", k = 2</span></p>
<p><strong>Output:</strong> <span class="example-io">""</span></p>
<p><strong>Explanation:</strong></p>
<ul>
<li>There is only one palindromic rearrangement: <code data-end="1112" data-start="1106">"aa"</code>.</li>
<li>The output is an empty string since <code>k = 2</code> exceeds the number of possible rearrangements.</li>
</ul>
</div>
<p><strong>Example 3:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">s = "bacab", k = 1</span></p>
<p><strong>Output:</strong> <span class="example-io">"abcba"</span></p>
<p><strong>Explanation:</strong></p>
<ul>
<li>The two distinct palindromic rearrangements of <code>"bacab"</code> are <code>"abcba"</code> and <code>"bacab"</code>.</li>
<li>Lexicographically, <code>"abcba"</code> comes before <code>"bacab"</code>. Since <code>k = 1</code>, the output is <code>"abcba"</code>.</li>
</ul>
</div>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>1 &lt;= s.length &lt;= 10<sup>4</sup></code></li>
<li><code>s</code> consists of lowercase English letters.</li>
<li><code>s</code> is guaranteed to be palindromic.</li>
<li><code>1 &lt;= k &lt;= 10<sup>6</sup></code></li>
</ul>
</div>
