
<h3>Minimum Operations to Sort a String</h3>
<div class="HTMLContent_html__0OZLp" data-qd-rendered-description="" data-track-load="description_content"><p data-end="244" data-start="156">You are given a string <code>s</code> consisting of lowercase English letters.</p>
<p>In one operation, you can select any <strong><span class="cursor-pointer relative text-dark-blue-s text-sm" data-keyword="substring-nonempty"><button aria-controls="radix-_r_t_" aria-expanded="false" aria-haspopup="dialog" class="" data-state="closed" type="button">substring</button></span></strong> of <code>s</code> that is <strong>not</strong> the entire string and <strong>sort</strong> it in <strong>non-descending alphabetical</strong> order.</p>
<p>Return the <strong>minimum</strong> number of operations required to make <code>s</code> sorted in <strong>non-descending</strong> order. If it is not possible, return -1.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">s = "dog"</span></p>
<p><strong>Output:</strong> <span class="example-io">1</span></p>
<p><strong>Explanation:</strong>​​​​​​​</p>
<ul>
<li>Sort substring <code>"og"</code> to <code>"go"</code>.</li>
<li>Now, <code>s = "dgo"</code>, which is sorted in ascending order. Thus, the answer is 1.</li>
</ul>
</div>
<p><strong>Example 2:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">s = "card"</span></p>
<p><strong>Output:</strong> <span class="example-io">2</span></p>
<p><strong>Explanation:</strong></p>
<ul>
<li>Sort substring <code>"car"</code> to <code>"acr"</code>, so <code>s = "acrd"</code>.</li>
<li>Sort substring <code>"rd"</code> to <code>"dr"</code>, making <code>s = "acdr"</code>, which is sorted in ascending order. Thus, the answer is 2.</li>
</ul>
</div>
<p><strong>Example 3:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">s = "gf"</span></p>
<p><strong>Output:</strong> <span class="example-io">-1</span></p>
<p><strong>Explanation:</strong></p>
<ul>
<li>It is impossible to sort <code>s</code> under the given constraints. Thus, the answer is -1.</li>
</ul>
</div>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>1 &lt;= s.length &lt;= 10<sup>5</sup></code></li>
<li><code>s</code> consists of only lowercase English letters.</li>
</ul>
</div>
