
<h3>Permutation in String</h3>
<div><p>Given two strings <code>s1</code> and <code>s2</code>, return <code>true</code> if <code>s2</code> contains a <span class="cursor-pointer relative text-dark-blue-s text-sm" data-keyword="permutation-string"><div class="popover-wrapper inline-block" data-headlessui-state=""><div><div aria-expanded="false" data-headlessui-state="" id="headlessui-popover-button-:rt:"><div>permutation</div></div><div style="position: fixed; z-index: 40; inset: 0px auto auto 0px; transform: translate(435px, 182px);"></div></div></div></span> of <code>s1</code>, or <code>false</code> otherwise.</p>
<p>In other words, return <code>true</code> if one of <code>s1</code>'s permutations is the substring of <code>s2</code>.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input:</strong> s1 = "ab", s2 = "eidbaooo"
<strong>Output:</strong> true
<strong>Explanation:</strong> s2 contains one permutation of s1 ("ba").
</pre>
<p><strong>Example 2:</strong></p>
<pre><strong>Input:</strong> s1 = "ab", s2 = "eidboaoo"
<strong>Output:</strong> false
</pre>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>1 &lt;= s1.length, s2.length &lt;= 10<sup>4</sup></code></li>
<li><code>s1</code> and <code>s2</code> consist of lowercase English letters.</li>
</ul>
</div>
