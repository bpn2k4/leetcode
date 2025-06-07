
<h3>Lexicographically Minimum String After Removing Stars</h3>
<div><p>You are given a string <code>s</code>. It may contain any number of <code>'*'</code> characters. Your task is to remove all <code>'*'</code> characters.</p>
<p>While there is a <code>'*'</code>, do the following operation:</p>
<ul>
<li>Delete the leftmost <code>'*'</code> and the <strong>smallest</strong> non-<code>'*'</code> character to its <em>left</em>. If there are several smallest characters, you can delete any of them.</li>
</ul>
<p>Return the <span class="cursor-pointer relative text-dark-blue-s text-sm" data-keyword="lexicographically-smaller-string"><button aria-controls="radix-:rfr:" aria-expanded="false" aria-haspopup="dialog" class="" data-state="closed" type="button">lexicographically smallest</button></span> resulting string after removing all <code>'*'</code> characters.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">s = "aaba*"</span></p>
<p><strong>Output:</strong> <span class="example-io">"aab"</span></p>
<p><strong>Explanation:</strong></p>
<p>We should delete one of the <code>'a'</code> characters with <code>'*'</code>. If we choose <code>s[3]</code>, <code>s</code> becomes the lexicographically smallest.</p>
</div>
<p><strong>Example 2:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">s = "abc"</span></p>
<p><strong>Output:</strong> <span class="example-io">"abc"</span></p>
<p><strong>Explanation:</strong></p>
<p>There is no <code>'*'</code> in the string.</p>
</div>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>1 &lt;= s.length &lt;= 10<sup>5</sup></code></li>
<li><code>s</code> consists only of lowercase English letters and <code>'*'</code>.</li>
<li>The input is generated such that it is possible to delete all <code>'*'</code> characters.</li>
</ul>
</div>
