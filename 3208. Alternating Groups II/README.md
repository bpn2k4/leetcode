
<h3>Alternating Groups II</h3>
<div><p>There is a circle of red and blue tiles. You are given an array of integers <code>colors</code> and an integer <code>k</code>. The color of tile <code>i</code> is represented by <code>colors[i]</code>:</p>
<ul>
<li><code>colors[i] == 0</code> means that tile <code>i</code> is <strong>red</strong>.</li>
<li><code>colors[i] == 1</code> means that tile <code>i</code> is <strong>blue</strong>.</li>
</ul>
<p>An <strong>alternating</strong> group is every <code>k</code> contiguous tiles in the circle with <strong>alternating</strong> colors (each tile in the group except the first and last one has a different color from its <strong>left</strong> and <strong>right</strong> tiles).</p>
<p>Return the number of <strong>alternating</strong> groups.</p>
<p><strong>Note</strong> that since <code>colors</code> represents a <strong>circle</strong>, the <strong>first</strong> and the <strong>last</strong> tiles are considered to be next to each other.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">colors = [0,1,0,1,0], k = 3</span></p>
<p><strong>Output:</strong> <span class="example-io">3</span></p>
<p><strong>Explanation:</strong></p>
<p><strong><img alt="" data-darkreader-inline-bgcolor="" data-darkreader-inline-bgimage="" src="assets/479bc1ee691f4ffc9badf62c065f8414.png" style="width: 150px; height: 150px; padding: 10px; background: rgb(255, 255, 255); border-radius: 0.5rem;"/></strong></p>
<p>Alternating groups:</p>
<p><img alt="" data-darkreader-inline-bgcolor="" data-darkreader-inline-bgimage="" src="assets/2d4e241a2d564567b5e72027dbe3a06e.png" style="width: 150px; height: 150px; padding: 10px; background: rgb(255, 255, 255); border-radius: 0.5rem;"/><img alt="" data-darkreader-inline-bgcolor="" data-darkreader-inline-bgimage="" src="assets/52503095bab6457db25f73b88e6fd424.png" style="width: 150px; height: 150px; padding: 10px; background: rgb(255, 255, 255); border-radius: 0.5rem;"/><img alt="" data-darkreader-inline-bgcolor="" data-darkreader-inline-bgimage="" src="assets/8b1e2686b7f04950947d13953e3a251d.png" style="width: 150px; height: 150px; padding: 10px; background: rgb(255, 255, 255); border-radius: 0.5rem;"/></p>
</div>
<p><strong>Example 2:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">colors = [0,1,0,0,1,0,1], k = 6</span></p>
<p><strong>Output:</strong> <span class="example-io">2</span></p>
<p><strong>Explanation:</strong></p>
<p><strong><img alt="" data-darkreader-inline-bgcolor="" data-darkreader-inline-bgimage="" src="assets/1b3640c8f15c4bbcb5d91801ff385ad6.png" style="width: 150px; height: 150px; padding: 10px; background: rgb(255, 255, 255); border-radius: 0.5rem;"/></strong></p>
<p>Alternating groups:</p>
<p><img alt="" data-darkreader-inline-bgcolor="" data-darkreader-inline-bgimage="" src="assets/e230058e50744869addc37d37215f057.png" style="width: 150px; height: 150px; padding: 10px; background: rgb(255, 255, 255); border-radius: 0.5rem;"/><img alt="" data-darkreader-inline-bgcolor="" data-darkreader-inline-bgimage="" src="assets/9d2428f14307499eb88d868a99750be1.png" style="width: 150px; height: 150px; padding: 10px; background: rgb(255, 255, 255); border-radius: 0.5rem;"/></p>
</div>
<p><strong>Example 3:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">colors = [1,1,0,1], k = 4</span></p>
<p><strong>Output:</strong> <span class="example-io">0</span></p>
<p><strong>Explanation:</strong></p>
<p><img alt="" data-darkreader-inline-bgcolor="" data-darkreader-inline-bgimage="" src="assets/b00aacda697041829b5912d59db7df7e.png" style="width: 150px; height: 150px; padding: 10px; background: rgb(255, 255, 255); border-radius: 0.5rem;"/></p>
</div>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>3 &lt;= colors.length &lt;= 10<sup>5</sup></code></li>
<li><code>0 &lt;= colors[i] &lt;= 1</code></li>
<li><code>3 &lt;= k &lt;= colors.length</code></li>
</ul>
</div>
